---
title: NAT
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
      I. NAT
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NAT의 정의
        </div>
        <div class="para-cntnt">
            1개의 실제 공인 IP 주소에, 다량의 가상 사설 IP 주소를 할당 및 매핑하는 주소변환 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. NAT
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NAT의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/NAT.png" alt="NAT">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. NAT의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형
  NAT 연결방법
    1 : 1 NAT - 주소와 주소가 1:1로 Mapping 되는 방식으로, 연결되지 않는 두 개의 네트워크 연결
    1 : N NAT - 하나의 주소에 여러 주소를 할당하여 1:N으로 Mapping 되는 방식 (공유기)
    N : M NAT - 내부 네트워크 IP 그룹과 외부 네트워크 IP 그룹끼리 매칭시켜 Mapping 
  IP 주소수정
    Source NAT - 패킷의 출발지(Source) IP 주소를 변경하는 것으로, 출발지의 IP 주소를 숨김, IP Masquerading
    Destination NAT - 패킷의 목적지(Destination) IP 주소를 변경하는 것, 방화벽이나 로드 밸런서
문제점
  여러 내부 IP가 하나의 외부 IP로 Mapping되는 경우에는 외부에서 내부로 데이터를 받을 때 문제
NAPT (Network Address Port Translation)
  NAT에 포트 정보를 추가한 개념으로, 하나의 외부 IP 주소로 전송해도 포트 번호로 호스트를 구별

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
