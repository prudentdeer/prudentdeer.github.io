---
title: Distance Vector, Link State 라우팅
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
      I. Distance Vector 라우팅
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Distance Vector, Link State 라우팅의 정의
        </div>
        <div class="para-cntnt">
          Link State 라우팅
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Distance Vector, Link State 라우팅
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Distance Vector, Link State 라우팅의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Distance-Vector,-Link-State-라우팅.png" alt="Distance Vector, Link State 라우팅">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Distance Vector, Link State 라우팅의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            라우터가 전체 네트워크 맵을 그리고 최소경로비용 기반 경로를 결정하는 라우팅 기법
비교
  경로설정 - 라우터 거리 더해 계산 &lt;&gt; Shortest path 계산 
  네트워크 - 소규모 네트워크 &lt;&gt; 대규모 네트워크
  프로토콜 - RIP (Routing Information Protocol) &lt;&gt; OSPF(Open Shortest Path First) 
  알고리즘 - 벨만포드 &lt;&gt; 다익스트라
  장점 - 라우터테이블 크기감소 &lt;&gt; 정보교환 오버헤드 감소
  단점 - 네트워크 변경에 느림 &lt;&gt; 큰 라우팅 테이블이 필요

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
