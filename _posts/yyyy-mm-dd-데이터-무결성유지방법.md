---
title: 데이터 무결성유지방법
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
      I. 데이터 무결성유지 방법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 무결성유지방법의 정의
        </div>
        <div class="para-cntnt">
          동시성제어 동이낙타락다
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 데이터 무결성유지방법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 무결성유지방법의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/데이터-무결성유지방법.png" alt="데이터 무결성유지방법">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 데이터 무결성유지방법의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            2PL - 모든 트랜잭션이 lock과 unlock 연산을 확장, 수축 단계로 나눠 수행
  타임스탬프 - 트랜잭션 간 순서를 미리 선택
  낙관적 검증 - 트랜잭션 종료 시에 일괄적으로 검사
  락킹
  다중버전동시성제어 MVCC
 
회복 회로체그아
  로그기반 - 즉시 갱신 기법, 지연 갱신 기법
  Check point - 로그 파일과 검사점을 이용한 복구
  Shadow paging - 트랜잭션 실행 동안 현재 페이지 테이블과 그림자 페이지 테이블 이용
  Aries

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
