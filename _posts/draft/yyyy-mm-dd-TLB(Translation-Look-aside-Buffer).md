---
title: TLB(Translation Look-aside Buffer)
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
      I. [정의] 자주 참조되는 가상메모리 주소를 실제 메모리 주소로 매핑 시 성능 개선을 위해 MMU(Memory Management Unit)에서 사용하는 고속 캐시
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. TLB(Translation Look-aside Buffer)의 정의
        </div>
        <div class="para-cntnt">
          [동작] TLB hit, TLB miss, Page fault(TLB write)
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. TLB(Translation Look-aside Buffer)
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. TLB(Translation Look-aside Buffer)의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/TLB(Translation-Look-aside-Buffer).png" alt="TLB(Translation Look-aside Buffer)">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. TLB(Translation Look-aside Buffer)의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          [태그] Dirty bit(write유무), Reference bit(참조유무)
[알고리즘] LRU
[성능향상] 페이지 크기 증대, 다중 페이지 지원

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
