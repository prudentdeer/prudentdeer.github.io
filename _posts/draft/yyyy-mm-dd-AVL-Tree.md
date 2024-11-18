---
title: AVL Tree
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 자료구조]
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
      I. AVL 트리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. AVL Tree의 정의
        </div>
        <div class="para-cntnt">
            왼쪽 서브트리 높이와 오른쪽 서브트리 Balance Factor 가 절대값 1 이하인 이진탐색 트리
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. AVL Tree
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. AVL Tree의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/AVL-Tree.png" alt="AVL Tree">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. AVL Tree의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          회전연산
  RR
  LL
  LR
  RL
특징
  Balance Factor - 균형 인수로 왼쪽 서브 트리의 높이 - 오른쪽 서브 트리의 높이 차이 값
  O(log n) - 시간 복잡도 검색, 삽입, 삭제에 O(log n) 시간 소요
AVL, Red-Black 트리 비교
  균형 - 엄격한 균형 &lt;&gt; 느슨한 균형
  동작 - LL, RR, RL, LR &lt;&gt; Restructuring, Recoloring
  검색 시간 - 상대적 빠름 &lt;&gt; 상대적 느림
  삽입, 삭제 시간 - 상대적 느림 &lt;&gt; 상대적 빠름
  시간복잡도 - O(log n) &lt;&gt; O(log n)
  공간복잡도 - 노드당 int Bit(Balance Factor 값) &lt;&gt; 노드당 1 Bit(Flag 반전, Red or Black)

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
