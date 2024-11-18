---
title: EDA
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 소프트웨어공학]
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
      I. 분산 비동기 처리 아키텍처, EDA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. EDA의 정의
        </div>
        <div class="para-cntnt">
            분산시스템간 이벤트 생성, 발행하고 필요로 하는 수신자에게 전송, 처리하는 PUB/SUB 아키텍처
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. EDA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. EDA의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/EDA.png" alt="EDA">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. EDA의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          토폴로지
  중재자 토폴로지 - 이벤트를 처리하기 위해 여러단계 존재, 오케스트레이션 중재자가 필요한 이벤트관리 토폴로지
  브로커 토폴로지 - 이벤트를 처리하기 위해 중재자 없이 이벤트와 응답을 직접 연관시키는 이벤트관리 토폴로지
구성요소 퍼프크 버프컨 중브
  Event Generator
    Publisher - 표준화된 형식의 이벤트를 생성
    Producer - 생성된 이벤트는 Event Channel로 전송
    Creator - 비동기 / 병렬 처리 가능
  Event Process Engine
    Event Bus - Event Generator에서 Event Processing Engine으로 수집된 데이터를 전파
    Event Processor - 수신한 이벤트를 식별/처리하는 역할
    Event Consumer - 처리 결과에 따라 새로운 이벤트를 생성
중재자, 브로커 토폴로지 비교
  역할 - 메시지 라우팅 &lt;&gt; 메시지 분배
  통신 - 패턴매칭, 라우팅 &lt;&gt; PUB, SUB 패턴
  구현 - 복잡성 증가 &lt;&gt; 비교적 간단
  확장성 - 확장 어려움 &lt;&gt; 수평적 확장 가능

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
