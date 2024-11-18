---
title: CDC
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 데이터베이스]
published: false
#tags: []
#pin: false
#math: false
#mermaid: false
#image:
#  path: /commons/devices-mockup.png
#  lqip: data:image/webp;base64,UklGRpoAAABXRUJQVlA4WAoAAAAQAAAADwAABwAAQUxQSDIAAAARL0AmbZurmr57yyIiqE8oiG0bejIYEQTgqiDA9vqnsUSI6H+oAERp2HZ65qP/VIAWAFZQOCBCAAAA8AEAnQEqEAAIAAVAfCWkAALp8sF8rgRgAP7o9FDvMCkMde9PK7euH5M1m6VWoDXf2FkP3BqV0ZYbO6NA/VFIAAAA
#  alt: Responsive rendering of Chirpy theme on multiple devices.
---

<div class="post-wrap">
  <div class="para">
    <div class="para-title">
      I. 로그기반 데이터 변경 적용, CDC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CDC의 정의
        </div>
        <div class="para-cntnt">
            DB 의 소스 시스템 변경데이터를 캡쳐하고, 운영 및 분석 시스템으로 실시간 전달해 주는 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. CDC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CDC의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/CDC.png" alt="CDC">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. CDC의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 타상트로 푸풀
  구현패턴
    타임스탬프 패턴 - 마지막 변경 시점을 기록하는 타임스탬프/버전 넘버 칼럼으로 레코드 변경 식별 
    상태 패턴 - 타임스탬프/버전 넘버 보완해 True/False Boolean 으로 변경 판단
    트리거 패턴 - DB 트리거 통한 타겟 시스템에 변경 배포하여 구현 
    로그기반 패턴 - 트랜잭션 로그에 대한 스캐닝 및 변경 내역을 통해 구현 
  구현방식 
    Push 방식 - 소스 DB에서 변경 식별에 타겟 DB에 변경 데이터 적재 
    Pull 방식 - 타겟DB에서 소스DB를 정기적 모니터링, 필요 시 다운로드
고려사항
  No Logging 트랜잭션 대응
  대량 데이터 처리 성능
  테이블 구조의 변경 연계
  암호화 데이터 처리

        </div>
      </div>
    </div>
  </div>

  <div class="refr-wrap">
    <div class="refr-title">
        참고자료
    </div>
    <ol class="refr-list">
    <!--    <li>(나현식, 최대선) <a target="_blank" href="https://scienceon.kisti.re.kr/commons/util/originalView.do?cn=JAKO202225948430499&oCn=JAKO202225948430499&dbt=JAKO&journal=NJOU00291864">메타버스 보안 위협 요소 및 대응 방안 검토</a></li>-->
    <!--    <li>(M. Uddin, S. Manickam, H. Ullah, M. Obaidat and A. Dandoush) <a target="_blank" href="https://ieeexplore.ieee.org/abstract/document/10138386">Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</a></li>-->
    </ol>
  </div>
</div>
