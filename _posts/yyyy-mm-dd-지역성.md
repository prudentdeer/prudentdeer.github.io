---
title: 지역성
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
      I. 지역성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 지역성의 정의
        </div>
        <div class="para-cntnt">
            CPU가 특정 순간에 기억장치의 특정 부분만 집중적으로 참조하는 지역적 특성
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 지역성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 지역성의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/지역성.png" alt="지역성">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 지역성의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          필요성
  Cache Access 시간을 최소화
  Cache 적중율 향상 극대화 달성
  Trashing 의 최소화
유형 시공순
  시간지역성 / Loop, Stack - 최근에 참조된 기억장소가 가까운 장래에 계속 참조
    Loop - for, while loop문 반복 수행
    Stack - 최근 참조 stack의 시간적 재사용
  공간지역성 / Array, Prefetch - 최근에 참조된 기억장소와 가까운 기억정보가 계속 참조
    Array - 저장위치 동일 배열원소 인출
    Prefetch - 사전 fetch 와 동일한 공간반복 
  순차지역성 / 순차처리
    순서처리 - 분기가 없는 한 기억장치에 저장된 순서대로 순차적 실행

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
