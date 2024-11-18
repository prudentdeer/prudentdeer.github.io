---
title: 레드-블랙 트리
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
      I. 레드-블랙 트리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 레드-블랙 트리의 정의
        </div>
        <div class="para-cntnt">
            각각의 노드가 Red 혹은 Black인 색상 속성을 가지고 있는 이진 탐색 트리
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 레드-블랙 트리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 레드-블랙 트리의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/레드-블랙-트리.png" alt="레드-블랙 트리">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 레드-블랙 트리의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  노드는 레드 혹은 블랙 중의 하나이다.
  루트 노드는 블랙이다.
  리프 노드들(NIL)은 블랙이다.
  레드 노드의 자식노드 양쪽은 언제나 모두 블랙이다. (즉, 레드 노드는 연달아 나타날 수 없으며, 블랙 노드만이 레드 노드의 부모 노드가 될 수 있다)
  새로 삽입되는 노드의 색은 무조건 Red 이다
연산 스컬
  Restructuring
  Recoloring
AVL, Red-Black 트리 비교
  균형 - 엄격한 균형 &lt;&gt; 느슨한 균형
  동작 - LL, RR, RL, LR &lt;&gt; Restructuring, Recoloring
  검색 시간 - 상대적 빠름 &lt;&gt; 상대적 느림
  삽입, 삭제 시간 - 상대적 느림 &lt;&gt; 상대적 빠름
  시간복잡도 - O(log n) &lt;&gt; O(log n)
  공간복잡도 - 노드당 int Bit(Balance Factor 값) &lt;&gt; 노드당 1 Bit(Flag 반전, Red or Black)
https://hongcoding.tistory.com/178

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
