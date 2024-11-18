---
title: 은행가 알고리즘
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 운영체제]
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
      I. 교착상태 예방 Banker 알고리즘
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 은행가 알고리즘의 정의
        </div>
        <div class="para-cntnt">
            교착상태를 예방하기위해 자원상태 감시, 안전상태 유지하는 교착상태 회피 알고리즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 은행가 알고리즘
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 은행가 알고리즘의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/은행가-알고리즘.png" alt="은행가 알고리즘">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 은행가 알고리즘의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 안불아만 AMAN 6954
  시스템상태
    안전상태 - 안전순서열 존재 / 교착상태를 일으키지 않고, 각 프로세스가 요구한 양만큼 자원을 할당해줄 수 있는 상태
    불안전상태 - 안전 순서열이 존재하지 않는 상태 / 아무런 방법이 없는 상태, 교착상태는 불안전 상태일 때만 발생
  자료구조
    Available - 사용 가능한 자원의 수 / Available[j]=K
    Max - 프로세스 별 최대 자원의 요구 / Max[i,j]=K
    Allocation - 현재 프로세스 별 할당되어 있는 자원 수 / Allocation[i,j]=K
    Need - 프로세스 별 남아있는 자원의 수 / Need[i,j]=(Max-Allocation)
은행가 알고리즘과 Wait-die 비교 요고기기 요고기종
  목적 - 교착상태 예방
  할당 - 미리계산 &lt;&gt; 동적결정
  기법 - AMAN &lt;&gt; Wait-die, Wound wait
  기준 - 안전상태 유지 &lt;&gt; Timestamp 기반

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
