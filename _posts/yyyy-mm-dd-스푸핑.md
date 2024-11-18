---
title: 스푸핑
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 보안]
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
      I. IP 프로토콜의 인증 취약점을 악용하는 IP Spoofing
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 스푸핑의 정의
        </div>
        <div class="para-cntnt">
            공격자가 IP를 공격하고자 하는 네트워크의 호스트의 IP로 바꿔 IP 기반인증 무력화 시키는 공격
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 스푸핑
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 스푸핑의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/스푸핑.png" alt="스푸핑">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 스푸핑의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          &lt;공격절차&gt; 및 상세설명
  1 : 공격자는 클라이언트에 TCP SYN Flooding 공격
  2 : 공격자는 클라이언트의 IP로 속여 서버에 연결을 요청
  3 : 서버는 클라이언트에서 온 패킷으로 알고 클라이언트에 SYN/ACK 패킷 전송
    클라이언트는 TCP SYN Flooding 공격 때문에 연결이 이루어지지 않아 서버가 보낸 패킷 확인 불가
  4 : 공격자는 클라이언트에서 ACK 패킷을 보낸 것처럼 속이면서 IP Spoofing 명령어가 들어있는 패킷을 보내 신뢰 관계에 있는 클라이언트라고 속이며 연결이 이루어짐
대응방안
  Static MAC 주소 사용, 모니터링, 관리적 보안, 패킷 필터링, TCP Wrapper SSH, 지속적 관리, Trusted 관계

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
