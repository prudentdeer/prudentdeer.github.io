---
title: DHCP
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
      I. IP 주소 자동 할당, DHCP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DHCP의 정의
        </div>
        <div class="para-cntnt">
            호스트에서 보유하고 있는 IP를 유동적으로 관리, 자동할당과 분배하는 네트워크 프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DHCP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DHCP의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DHCP.png" alt="DHCP">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DHCP의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          동작단계 도라 DORA
  Discover - DHCP 서버를 찾는 요청을 Broadcast하는 과정
  Offer - 사용가능한 IP Address 하나를 담아 Packet을 만들어 Broadcast하는 과정
  Request - Packet을 만들어 네트워크 내 DHCP서버로 승인요청을 보내는 과정
  Ack - IP Address가 채택되지 않았을 경우, IP Database에 유지하고, 채택되었을 Packet을 만들어서 Broadcast
구성요소 클서디풀서
  DHCP 클라이언트 - 시스템이 시작됨과 동시에 DHCP 서버를 찾는 메시지를 네트워크에 발송, IP 주소 임대 요청
  DHCP 서버 - 클라이언트의 요청에 응답하여 자신의 DHCP DB에서 IP 주소를 임대
  DHCP DB - DHCP 클라이언트가 할당되거나 해당 TCP/IP 주소 임대를 해제할 때 업데이트 되는 동적 DB
  IP 주소풀 - DHCP 클라이언트에서 이용가능한 IP 주소 범위
  서브넷 - IP 네트워크 분할
할당 메커니즘 자수동
  자동 할당 - 클라이언트에게 영구적인 IP 할당 기법
  수동 할당 - 클라이언트의 P 주소를 네트워크 관리자가 할당하고 DHCP는 그 주소를 할당하는 기법
  동적 할당 - 클라이언트에게 한정된 시간 동안 IP 할당 기법, 3가지 메커니즘 중에서 유일하게 IP 재사용

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
