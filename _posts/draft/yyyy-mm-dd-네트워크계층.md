---
title: 네트워크계층
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
      I. 네트워크 계층, 3계층
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 네트워크계층의 정의
        </div>
        <div class="para-cntnt">
            송신자, 수신자 간 Data 전송을 위해 Logical Address를 지정하고 이를 통해 포워딩과 라우팅을 수행할 수 있도록 지원하는 계층
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 네트워크계층
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 네트워크계층의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/네트워크계층.png" alt="네트워크계층">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 네트워크계층의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          프로토콜
  IP - 호스트의 주소지정과 패킷 분할 및 조립 기능을 담당
  ICMP - TCP/IP에서 IP 패킷을 처리할 때 발생되는 문제(오류 보고)를 알림 (Internet Control Message Protocol)
  IGMP - IP 멀티캐스트를 실현하기 위한 통신 프로토콜
  ARP - 논리적인 IP 주소를 (망계층), 물리적인 MAC 주소로 (데이터링크 계층) 바꾸어주는 역할을 하는 주소 해석 프로토콜 / Proxy ARP, Gratuitous ARP, RARP

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
