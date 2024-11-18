---
title: Belady's Anomaly
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
      I. FIFO 교체 모순, Belady's Anomaly
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Belady's Anomaly의 정의
        </div>
        <div class="para-cntnt">
            FIFO 페이지교체시, 페이지 프레임수가 늘었지만 page fault 발생이 오히려 증가하는 현상
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Belady's Anomaly
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Belady's Anomaly의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Belady's-Anomaly.png" alt="Belady's Anomaly">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Belady's Anomaly의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          사례
  [1 2 3 4 1 2 5 1 2 3 4 5]
  3page -&gt; 9 fault
  4page -&gt; 10 fault
해결방안
  페이지 교체기법 변경 
    LRU 사용 - 페이지 교체시점에서 가장 최근에 참조가 안된 페이지를 교체하는 기법 
    OPT 사용 - 앞으로 가장 오랫동안 사용하지 않을 페이지를 교체하는 기법
  최적화 설계 
    WSM - 시간적, 공간적, 순차적 지역성 활용, Working Set 
    PFF - 프로세스의 페이지 폴트 빈도에 따라 Residence Set을 조정
- 쓰레싱 발생가능성

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
