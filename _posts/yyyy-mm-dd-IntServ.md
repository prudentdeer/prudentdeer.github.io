---
title: IntServ
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
      I. 통합 서비스모델, IntServ
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IntServ의 정의
        </div>
        <div class="para-cntnt">
            종단간 트래픽 흐름 단위 경로상 라우터 자원을 미리예약해 종단간 QoS 보장하는 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IntServ
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IntServ의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IntServ.png" alt="IntServ">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IntServ의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          IntServ 서비스 종류
  Guaranteed Service / 보장형 : 용량이나 전송 속도 면에서 확신한 수준 서비스 제공
  Controlled Load Service / 제어부하형 : 부하가 없는 상태에서 Best-effort 서비스가 받는 수준의 QoS를 제공
구성요소 STAR STC
  Service class : 어플리케이션이 받고자 하는 서비스 클래스를 선택
  Traffic descriptor : 어플리케이션 자신의 트래픽 특성과 QoS요구사항 기술
  Admission control : 라우터 내의 가용 자원을 고려하여 어플리케이션이 요청 한 서비스를 수락할지 여부를 결정
  Reservation (RSVP) : 호스트가 라우터에 또는 라우터가 인접한 다른 라우터에게 트래픽 특성, QoS 요구사항을 전달
  Scheduler : 패킷을 요청한 서비스와 QoS에 기준하여 전달 순서결정
  Traffic control : 트래픽 계약을 기준으로 Policing, Dropping, Shapping을 수행
  Classfier : 입력된 패킷이 어느 Flow에 해당하는 지를 판별

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
