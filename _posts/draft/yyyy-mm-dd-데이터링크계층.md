---
title: 데이터링크계층
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
      I. 데이터링크 계층, 2계층
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터링크계층의 정의
        </div>
        <div class="para-cntnt">
            직접연결 노드사이 데이터 전송보장, 흐름제어 및 오류수정의 기능을 담당하는 계층
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 데이터링크계층
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터링크계층의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/데이터링크계층.png" alt="데이터링크계층">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 데이터링크계층의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          프로토콜
  Ethernet - 비연결성 모드, 전송속도 10Mbps 이상, LAN 구현 방식을 말함
  HDLC - 고속 데이터 전송에 적합, 비트 전송을 기본으로 하는 범용의 데이터 링크 전송제어절차
  PPP - 전화선 같이 양단간 비동기 직렬 링크를 사용하는 두 컴퓨터간의 통신을 지원하는 프로토콜
역할 정오흐주접
  정보전달 - 인접 노드간 송신측에서 최종 수신측으로 데이터를 전송 / 오류제어, 흐름제어
  오류제어 - Data가 통신로를 통과하는 동안에 오류를 검사 / CRC, BEC, 해밍코드, FEC
  흐름제어 - 수신측에 Frame을 전달하고자 할 때 수신측에서 처리할 수 있는 데이터 양을 조정 / ARQ
  주소지정 - 헤더와 트레일러 안에는 데이터를 최종적으로 보낸 송신자와 물리주소와 다음으로 보낼 수신지의 물리 주소가 삽입되어 있음 / LLC, MAC
  접근제어 - 서로 다른 시스템이 동일한 링크에 연결되어 있을 때 그 링크를 어떤 시점에서 점유하고자 할 때 접근 방식을 제어 / CSMA/CD, CSMA/CA
장비 
  L2 Switch

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
