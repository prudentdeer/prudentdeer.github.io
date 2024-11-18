---
title: IPv4
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
      I. &lt;네트워크 주소 식별체계, 네트워크 IP주소의 개요&gt;
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IPv4의 정의
        </div>
        <div class="para-cntnt">
            인터넷에 연결되어 있는 장치구별 위해 TCP/IP 의 IP계층에서 사용하는 32비트 식별가능 주소체계
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IPv4
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IPv4의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IPv4.png" alt="IPv4">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IPv4의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
&nbsp; &nbsp;유일성 : IP 주소는 인터넷에 오직 한 개의 연결만을 정의 중복 불가능
유형
  IPv4 : 32비트 이진수를 각각 8비트씩 네 부분으로 나누고, 점(.)으로 구분하여 10진수 표기
  IPv6 : 이진수를 각각 16비트씩 여덟 부분으로 나누고 각 부분을 콜론(:)으로 구분하여 16진수 표기
  NIC : Network Information Center에서 할당 및 관리
&lt;주소체계&gt; 와 상세설명
  클래스명 / 초기비트 / NetID / HostID / 주소영역
  A / 0xxx / 7비트 / 24비트 / 0.0.0.0~127.255.255.255
  B / 10xx / 14비트 / 16비트 / 128.0.0.0~191.255.255.255
  C / 110x / 21비트 / 8비트 / 192.0.0.0~223.255.255.255
  D / 1110 / 다중방송용 주소(멀티캐스트) / 224.0.0.0~239.255.255.255
  E / 1111 / 예약 주소(향후 사용) / 240.0.0.0~255.255.255.255

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
