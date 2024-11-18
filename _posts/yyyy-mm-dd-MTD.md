---
title: MTD
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 보안]
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
      I. 능동적 사이버보안 기술, MTD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MTD의 정의
        </div>
        <div class="para-cntnt">
            보호 대상의 주요속성을 변화시켜 사이버 공격을 사전에 차단하는 능동적 보안 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MTD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MTD의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MTD.png" alt="MTD">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MTD의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 셔다리디
  Shuffle
    네트워크주소 랜덤화 - SDN, NAT, Virtual Gateway 적용 네트워크 주소 변경
    메모리주소 재지정 - 주기적 메모리 주소 재할당 통한 공격 대응
  Diversity
    OS별 환경구성 - 플랫폼 내 OS별 환경 구성 통한 공격 비용 증가 
    플랫폼 분리 - 동일 기능을 다양한 플랫폼으로 구현하여 공격 방어
  Redundancy
    동적 Instance 구성 - 동일 Instance를 중복 생성하여 공격 시 Instance 종료 
    동일 서비스 운영 - 동일 서비스 운영 통한 공격 발생 시 피해 최소화
  Distribution
    분산 저장 - 데이터 탈취 및 훼손 발생 시 복구 위한 분산 저장
    분산 실행 - 다중 분산 환경 내 실행을 통한 공격 대상 다양화

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
