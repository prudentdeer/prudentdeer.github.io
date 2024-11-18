---
title: EAI
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 경영전략]
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
      I. E-비즈니스를 위한 기본 인프라, EAI
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. EAI의 정의
        </div>
        <div class="para-cntnt">
            이종 애플리케이션을 통합하여 어댑터, 미들웨어 기반 하나의 시스템 관리 통합 시스템
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. EAI
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. EAI의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/EAI.png" alt="EAI">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. EAI의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 플어브워
  EAI 플랫폼 - 데이터무결성 위한 메시지큐와 트랜잭션 수행, 대규모 환경까지 확장성 보장
  어댑터 - 다양한 패키지 및 추가 위한 재사용성 인터페이스 지원
  브로커 - 상호간 데이터전송을 위한 포맷과 코드변환
  워크플로우 - 미리 정의한 프로세스에 따라 앱간 데이터 전달
구축유형 포허메하피
  Point to Point - 가장 기초적인 1:1 통합방법 / 솔루션 구매하지 않음
  Hub &amp; Spoke -  앱 사이에 미들웨어를 두어 처리하는 중앙집중형 방식 / 데이터 전송보장
  Messaging Bus - 앱 사이에 버스와 어댑터를 두어 처리하는 방식 / 확장성, 대용량처리
  Hybrid - Hub &amp; Spoke와 Messaging Bus 방식의 혼합형 / 그룹 내 Hub &amp; Spoke,  그룹간 Messaging Bus
  Peer to Peer - 중간 미들웨어를 두지 않고, 각 앱이 PeerServer가 되어 Point-to-Point 연결 / Star 형태

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
