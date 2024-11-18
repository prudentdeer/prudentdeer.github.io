---
title: 비선점방식 스케줄링
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
      I. 공정한 스케줄링 방법, 비선점 방식 스케줄링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 비선점방식 스케줄링의 정의
        </div>
        <div class="para-cntnt">
            프로세스가 CPU를 할당받으면 반환시까지 다른 프로세스는 점유불가한 CPU 스케줄링 방법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 비선점방식 스케줄링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 비선점방식 스케줄링의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/비선점방식-스케줄링.png" alt="비선점방식 스케줄링">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 비선점방식 스케줄링의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          비선점방식의 종류 우기피소희
  우선순위 스케쥴링 (Priority)
    - 각 프로세스에 우선순위가 주어지고 우선순위에 따라 CPU 할당
    - 우선순위가 높은 작업이 계속적으로 들어오게 될 우선순위가 낮은 프로세스는 Starvation 발생 → Aging 기법으로 해결가능
  기한부 스케줄링 (Deadline)
    - 작업들이 명시된 시간이나 기한 내에 완료되도록 계획하고, 사용자는 사전에 작업이 요구하는 정확한 자원을 제시
    - 작업시간이나 상황 등 정보를 미리 예측하기가 어려움
  FCFS (First Come First Service = FIFO)
    - 프로세스가 대기큐(준비큐)에 도착한 순서에 따라 CPU 할당
    - Convoy Effect 발생 가능 (Burst time이 긴 프로세스가 CPU 독점)
    - 단독적 사용이 거의 없으며, 다른 스케줄링 알고리즘에 보조적으로 사용 (우선순위 스케줄링, RR 스케줄링 등)
  SJF (Shortest Job First)
    - 준비 상태 큐에 있는 프로세스들 중에 실행시간이 짧은 프로세스에게 먼저 CPU 를 할당하는 기법
    - CPU 요구시간이 긴 작업과 짧은 작업간의 불평등
    - CPU 요구시간이 긴프로세스는 Starvation 발생 → HRN 사용
  HRN (Highest Response Ratio Next)
    - 대기 프로세스 중 우선순위(Response Ratio)가 높은 작업을 먼저 수행하는 알고리즘 
    - 준비 상태 큐에 있는 프로세스들 중에 우선순위가 높은 프로세스에게 먼저 CPU를 할당하는 기법
    - SJF의 약점을 보완한 기법으로 긴 작업과 짧은 작업간의 불평등을 완화

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
