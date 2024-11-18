---
title: B-Tree
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
      I. Balanced Tree, B-Tree
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. B-Tree의 정의
        </div>
        <div class="para-cntnt">
            리프노드를 제외한 모든 노드는 2개 이상의 자식 노드를 가지는 이진트리
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. B-Tree
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. B-Tree의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/B-Tree.png" alt="B-Tree">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. B-Tree의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            예) AVL Tree, 2-3 tree(이삼트리), Red-Black Tree 등이 있음

- Balanced - Tree 의 일종
- B 트리는 하나의 노드에 여러 자료가 배치되는 트리구조
- 한 노드에 M개의 자료가 배치되면 M차 B 트리라고 함
- 데이터베이스와 파일시스템에 널리 사용
- 노드 내의 데이터는 오름차순으로 정렬
- 모든 말단 노드는 항상 레벨이 같음
- 새로운 값은 항상 말단노드에 삽입

https://velog.io/@chanyoung1998/B%ED%8A%B8%EB%A6%AC

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
