---
title: AODV
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
      I. AODV
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. AODV의 정의
        </div>
        <div class="para-cntnt">
            adhoc 네트워크상에서 on-demand 하며 distance vector 알고리즘을 쓰는 라우팅 방식
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. AODV
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. AODV의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/AODV.png" alt="AODV">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. AODV의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형
  RREQ - RREQ메세지는 전달되면서 거쳐간 노드들의 주소와 Hop 수를 기록
  RREP - 목적지가 RREQ 패킷을 받게되면 RREP 메시지를 역방향 최단 피드백 루트로 전달
장점
  on-demand 동적 라우팅 경로 구성으로 경량화
단점 
  경로 손실, 악의적인 패킷전달 방해복구에 있어 효율이 떨어짐

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
