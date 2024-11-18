---
title: MQMS
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
      I. 멀티 큐 멀티프로세서 스케쥴링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MQMS의 정의
        </div>
        <div class="para-cntnt">
            여러 개의 Queue를 활용하여 N개의 코어로 처리하는 스케줄링 방식
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MQMS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MQMS의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MQMS.png" alt="MQMS">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MQMS의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          장점
  확장성이 좋음 - CPU는 각각 하나 또는 그 이상의 큐를 가지며 각각의 큐는 RR과 같은 특정한 스케줄링 방법을 사용
  캐시 친화적 - 작업이 같은 CPU 에서 계속 실행되기 때문에 캐시에 저장된 내용을 재사용하는 이점을 가짐
단점 
  구현복잡 - 단일큐에 비해 구현이 복잡
  워크로드 불균형 - CPU 하나가 유휴 상태인 워크로드의 불균형 (load imbalance) 문제 발생 가능
문제점
   특정 CPU가 유휴상태인 워크로드의 불균형(load imbalance) 문제가 발생
해결방안
  - Migration을 통해 B, D 프로세스 중 하나를 Q0로 옮기는 작업을 수행
  - Work stealing 통해 프로세스들을 적절한 큐로 계속 이동시켜 워크로드 불균형 해결 가능
  - 너무 자주 Work stealing 수행하게되면 오버헤드가 발생할 수 있으므로 적절히 조율

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
