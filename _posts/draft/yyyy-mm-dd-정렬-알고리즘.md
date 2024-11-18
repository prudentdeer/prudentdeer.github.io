---
title: 정렬 알고리즘
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 알고리즘]
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
      I. 자료의 순서화 작업, 정렬 알고리즘
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 정렬 알고리즘의 정의
        </div>
        <div class="para-cntnt">
            원소로 구성된 리스트에서 특정 규칙에 의해 원소들을 일정한 순서대로 재배치 하는 알고리즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 정렬 알고리즘
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 정렬 알고리즘의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/정렬-알고리즘.png" alt="정렬 알고리즘">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 정렬 알고리즘의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 버병삽 선힙퀵
  순서보장 알고리즘
    버블정렬 / Swap - 서로 인접한 두 자료의 대소를 비교하고, 자리를 교환하며 정렬하는 알고리즘
    병합정렬 / Split, Merge - 리스트를 두개의 균등크기 반복분할, 분할부분을 정렬하면서 합병
    삽입정렬 / Insert - 두 번째 자료부터 앞의 자료과 비교, 자리에 삽입 정렬알고리즘
  순서 미보장 알고리즘
    선택정렬 / Min, Switch - 집합 중 최솟값, 최대값을 선택하여 배열의 첫 번째 요소와 교환
    힙 정렬 / Down heap, Up heap - 우선순위 큐를 이용해 다운 힙, 업 힙 연산으로 정렬
    퀵 정렬 / Pivot, Divide, Conquer - 리스트 Pivot 비균등 Divide 하고 각각 정렬 후 Combine  
성능
  Best / Avg / Worst 
  버블정렬 - n^2 / n^2 / n^2
  병합정렬 - nlog2n / nlog2n / nlog2n
  삽입정렬 - n / n^2 / n^2
  선택정렬 - n^2 / n^2 / n^2
  힙정렬 - nlog2n / nlog2n / nlog2n
  퀵정렬 - nlog2n / nlog2n / n^2

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
