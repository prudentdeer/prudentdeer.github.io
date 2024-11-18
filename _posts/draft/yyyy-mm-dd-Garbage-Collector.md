---
title: Garbage Collector
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 컴퓨터구조]
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
      I. [정의] Java Application 동작 시, 더 이상 참조되지 않는 메모리를 자동 수거하는 기능으로 Java언어  메모리 최적화 기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Garbage Collector의 정의
        </div>
        <div class="para-cntnt">
          알고리즘  
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Garbage Collector
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Garbage Collector의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Garbage-Collector.png" alt="Garbage Collector">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Garbage Collector의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            (1) Full GC (Old영역 GC) : Reference연결안된 객체 Mark&amp;삭제 / Mark &amp; Compact
  (2) Minor GC (Young, Old) : 오래된 객체를 Old 영역으로 이동 / copy &amp; scavenge
  (3) Incremental GC(Train GC) : Minor GC수행 시 Full GC영역을 조금씩 수행
       , Full GC 횟수와 시간 줄이는 방법 
  (4)G1: 최근 성능강점, 미검증

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
