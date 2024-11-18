---
title: SQMS
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
      I. 싱글 큐 멀티프로세서 스케줄링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SQMS의 정의
        </div>
        <div class="para-cntnt">
            하나의 Queue를 활용하여 N개의 코어로 처리하는 스케줄링 방식
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SQMS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SQMS의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SQMS.png" alt="SQMS">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SQMS의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          장점
  구현이 간단함 - 기존의 단일 CPU 스케줄러가 있다면 하나의 큐밖에 없기 때문에 구현이 간단
  변경이 적음 - 기존 정책을 다수 CPU에서 동작하도록 하는 데는 많은 변경이 필요치 않음
단점
  확장성 부족 - 동기화 오버헤드 때문에 확장성 결여(a lack of scalability)
  캐시선호도 저하 - 캐시 선호도(Cache Affinity)에 문제가 있음
문제점
  - 작업이 실행되는 CPU가 변경되면서 캐시 선호도(Cache Affinity)에 문제 발생
해결방안
  - 캐시 선호도를 고려한 스케줄링 방식을 적용
  - 캐시 선호도가 적용되지 않는 프로세스가 존재할 수 있음
  - SQMS의 구현체는 대부분 캐시 선호도를 보존하기 위한 알고리즘을 포함하고 있음

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
