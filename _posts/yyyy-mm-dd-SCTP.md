---
title: SCTP
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
      I. 차세대 전송 계층 프로토콜, SCTP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SCTP의 정의
        </div>
        <div class="para-cntnt">
            RFC 2960 표준 TCP 의 신뢰성과 UDP 의 속도보장을 조합한 전송 계층 프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SCTP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SCTP의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SCTP.png" alt="SCTP">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SCTP의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  신뢰성 - TCP와 마찬가지로 데이터의 신뢰성 있는 전송을 보장 
  메시지 지향 - UDP와 유사하게 메시지 경계를 유지하면서 데이터를 전송  
  멀티호밍 - SCTP 세션이 여러 개의 IP 주소를 동시에 사용할 수 있도록 하며 장애 발생시 대체 경로를 통해 세션 유지
  멀티스트리밍 - 하나의 세션을 통해 다양한 종류의 응용데이터를 보내는 기술
구성요소 포식청 전식순
  패킷구조
    Port / 포트 - source, destination 포트주소
    VerificationTag / 세션식별자 – Association 별 할당 사용 /
    Data chunk / 데이터청크 – 실제 데이터를 전송하는 단위 / 
  청크구조
    TSN / 전송순서번호 – 세션에 대한 흐름제어 및 오류복구
    SI / 스트림식별자 – 데이터스트림 식별에 사용
    SSN / 스트림순서번호 – 전송 순서를 관리
동작방식
  연결 / 4-Way Handshake 인액쿠액
    &gt; INIT    &lt; INIT-ACK    &gt; COOKIE-ECHO    &lt; COOKIE-ACK
  종료 / 3-Way Handshake 셧액컴
    &gt; SHUTDOWN    &lt; SHUTDOWN-ACK    &gt; SHUTDOWN-CMPL

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
