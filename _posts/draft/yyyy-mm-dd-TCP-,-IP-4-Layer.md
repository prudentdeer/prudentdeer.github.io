---
title: TCP / IP 4 Layer
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
      I. Defacto 네트워크모델, TCP/IP 4 Layer
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. TCP / IP 4 Layer의 정의
        </div>
        <div class="para-cntnt">
            네트워크 통신시 발생 문제완화 위해, 현장에서 사용하는 4계층 defacto 네트워크 모델
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. TCP / IP 4 Layer
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. TCP / IP 4 Layer의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/TCP-,-IP-4-Layer.png" alt="TCP / IP 4 Layer">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. TCP / IP 4 Layer의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          TCP/IP 4계층 응전네인
  상위계층
    응용계층 - 개발자 구현계층 / HTTP, FTP, SMTP, POP3, TELNET
    전송계층 - 통신노드간 연결제어, 자료 송수신 / TCP, UDP
  하위계층
    네트워크 - 통신노드간 IP 패킷 전송하는 계층 / IP, ARP, ICMP, IGMP
    네트워크 IF - 물리장비 식별위해 MAC 주소 사용계층 / MAC, LAN, 위성통신
OSI 7 Layer 와 TCP/IP 비교
  목적 - 모델 표준 제시 &lt;&gt; 네트워크 통신 구현
  계층수 - 7계층 &lt;&gt; 4계층
  속성 - 표준 참조 모델 &lt;&gt; 프로토콜 규약
  특성 - 정형성, 규칙성 &lt;&gt; 유연성(연결/비 연결)
  표준 - De Jure Standard (법률표준) &lt;&gt; De Facto Standard (사실표준)

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
