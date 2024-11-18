---
title: Priority Queue, PQ
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
      I. 우선순위 큐, Priority Queue
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Priority Queue, PQ의 정의
        </div>
        <div class="para-cntnt">
            데이터에 우선순위를 부여하여 우선순위가 높은 데이터가 먼저 나갈수 있도록 구현한 큐
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Priority Queue, PQ
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Priority Queue, PQ의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Priority-Queue,-PQ.png" alt="Priority Queue, PQ">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Priority Queue, PQ의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            - 우선순위 큐는 힙이 아니고 추상적 개념, 보통 힙으로 구현함
연산
  Enqueue() - queue에 새 요소 삽입
  Dequeue() - queue에서 최대 우선 순위 요소를 삭제하고 그 값을 반환
  Peek() - queue에서 최대 우선순위 요소를 반환
  Heapify() - 힙 속성을 유지하는 작업
구현유형
  Array사용(순서없는, 정렬된)
  Linked List사용(순서없는, 정렬된)
  Heap사용(최대/최소)
https://yoongrammer.tistory.com/81

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
