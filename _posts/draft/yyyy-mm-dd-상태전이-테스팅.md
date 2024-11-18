---
title: 상태전이 테스팅
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 소프트웨어공학]
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
      I. 시스템 상태변화에 따른 측면을 고려한 상태전이 테스팅
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 상태전이 테스팅의 정의
        </div>
        <div class="para-cntnt">
            테스트 대상 상태를 구분하고, 다른 상태로 전이되는 테스트 케이스 구성 테스트 설계기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 상태전이 테스팅
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 상태전이 테스팅의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/상태전이-테스팅.png" alt="상태전이 테스팅">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 상태전이 테스팅의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          표기법 상전이가액션
  상태 - 이벤트 대기 시스템
  전이 - 다른상태로의 변경
  이벤트 - 상태전이 유발요인
  가드 - 이벤트 발생조건
  액션 - 상태전이로 인한 유발동작
설계방식
  상태 (순서, 모든상태)
  전이 (모든 상태 전이, 특정한 상태 전이, 블가능한 상태 전이)

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
