---
title: B+ Tree
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
      I. B+ Tree
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. B+ Tree의 정의
        </div>
        <div class="para-cntnt">
            모든 Key, Data가 리프노드에 모든 Data를 가지고 있는 데이터 탐색에 특화된 이진트리
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. B+ Tree
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. B+ Tree의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/B+-Tree.png" alt="B+ Tree">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. B+ Tree의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          
- 모든 리프노드가 연결리스트의 형태를 띄고 있음
- 리프노드의 부모 key는 리프노드의 첫번째 key보다 작거나 같음 
[목적] 순차검색 향상을 위해 인덱스 set과 순차 set 구상
[구성요소]
Index Set, Sequence Set

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
