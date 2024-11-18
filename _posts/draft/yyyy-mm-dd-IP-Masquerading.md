---
title: IP Masquerading
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
      I. IP Masquerading
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IP Masquerading의 정의
        </div>
        <div class="para-cntnt">
            출발지의 IP 주소를 숨기기 위해 패킷의 출발지 IP 주소를 변경하는 IP 위장 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IP Masquerading
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IP Masquerading의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IP-Masquerading.png" alt="IP Masquerading">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IP Masquerading의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          
다수의 private IP를 1개의 public IP로 변환
LInux의 IP Masquerade가 이것을 구현한 것이고, 공유기 등에서 거의 필수적으로 존재하는 기능입니다.

단 하나의 공인 IP로 내부 모든 PC가 대표 IP 주소를 공유 사용
- IP 계층,전송 계층 모두에서 변환(맵핑)으로, 마치 가면(위장,Masquerading) 효과 있음

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
