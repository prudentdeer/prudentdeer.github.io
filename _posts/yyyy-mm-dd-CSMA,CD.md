---
title: CSMA/CD
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 네트워크]
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
      I. 다중접속 및 충돌탐지, CSMA/CD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CSMA/CD의 정의
        </div>
        <div class="para-cntnt">
            유선랜 환경에서 충돌최소화 위해 전송전 공유매체 사용확인, 전송후 충돌발생 확인 프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. CSMA/CD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CSMA/CD의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/CSMA,CD.png" alt="CSMA/CD">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. CSMA/CD의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          동작절차
  채널감시 - 다른호스트의 채널사용여부 검사
  데이터송신 - 채널이 빈 상태면 전송 시작
  채널감시 - 전송하는 동안 지속 채널 감시
  JAM전송 - 전송중지, 충돌알리는 JAM 신호 전송  
  Backoff - 채널이 사용중이면 대기, 감시
재전송
  재시도마다 backoff시간 2배씩 증가
  16번 충돌발생 - 전송중지 - 에러보고
무선랜에서 CSMA/CD 사용 못하는 이유
  - 낮은 전력으로 한번에 송신, 수신 하나만 가능 
  - 숨은 지극이 존재
  - 기지국 간의 거리가 장거리 일 수 있음

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
