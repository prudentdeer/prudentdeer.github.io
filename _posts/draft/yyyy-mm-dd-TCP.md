---
title: TCP
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
      I. 신뢰성 있는 데이터 통신 지원, TCP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. TCP의 정의
        </div>
        <div class="para-cntnt">
            RFC 793 표준 오류제어, 흐름제어, 혼잡제어 제공 연결지향 신뢰보장 전송계층 프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. TCP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. TCP의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/TCP.png" alt="TCP">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. TCP의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  연결지향 - 패킷 손실, 중복, 순서바뀜 등이 없도록 보장
  신뢰기반 - 양종단 호스트 내 프로세스 상호 간에 신뢰적인 연결지향성 서비스
연결관리
  연결 / 3 Way Handshake - SYN - (SYN + ACK) - ACK
  종료 / 4 Way Handshake - FIN - ACK - FIN - ACK
TCP Timer 재지킵타
  재전송 타이머 - TCP가 신뢰성 있는 전송을 위해 사용, 패킷 전송과 동시에 재전송타이머 동작
  지속 타이머 - 윈도우 크기가 0인 세그먼트를 수신하게 되면 새로운 세그먼트 전송 중지
  Keep Alive Timer - 데이터 교환 없이 오랜 시간 Idle 상태로 있는 것 방지
  Time-Waited 타이머 - TCP 연결 해지 용도, 마지막 세그먼트 수신 후 즉시 종료하는 것이 아닌 연결 유지

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
