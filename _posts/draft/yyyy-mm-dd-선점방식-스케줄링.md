---
title: 선점방식 스케줄링
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
      I. 규칙에 의한 자원선점, 선점방식 스케줄링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 선점방식 스케줄링의 정의
        </div>
        <div class="para-cntnt">
            우선순위가 높은 프로세스가 현재 프로세스를 중단시키고 CPU를 선점하는 스케줄링 방법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 선점방식 스케줄링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 선점방식 스케줄링의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/선점방식-스케줄링.png" alt="선점방식 스케줄링">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 선점방식 스케줄링의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 RS 멀레
  Round Robin 
    - FCFS 방식으로 프로세스를 대기큐에 저장
    - 할당된 CPU 시간내에 처리 못한 프로세스는 대기큐의 가장 뒤로 이동
    - CPU는 대기큐의 다음 프로세스를 수행
  SRTF (Shortest Remaining Time First)
    - 매 주기마다, 까지 가장 짧은시간이 소요되는 프로세스가 CPU를 선점하여 수행
  Multi-Level Queue
    - 작업을 여러 종류 그룹으로 누어 다수의 큐를 이용하는 기법
    - 비 상태 큐를 여러 종류로 분할
    - 다른 큐로 작업 이동 불가
  Multi-Level Feedback Queue
    - 입출력 위주, CPU위주인 프로세스 특성에 따라 서로 다른 CPU time slice를 부여
    - 수행 후 점차 낮은 우선순위 부여 (맨 마지막 단계에서는 Round Robin 처리)
  RM 스케줄링 (Rate Monotonic)
    - 시간당 CPU 사용률을 계산하여 프로세스들을 이상 없이 수행할 수 있도록 지원하는 실시간 시스템을 위한 정적(고정) 스케쥴링 정책
    - 각 task 의 수행주기가 가장 짧은 프로세스에 가장 높은 우선순위를 부여하는 방식
  EDF 스케줄링 (Early Deadline First)
    - 프로세스를 우선순위 큐를 통해 수행
    - 준비된 프로세스들 중 마감시간이 가장 가까운 프로세스를 탐색하여 가장 먼저 수행하는 동적 스케쥴링 정책

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
