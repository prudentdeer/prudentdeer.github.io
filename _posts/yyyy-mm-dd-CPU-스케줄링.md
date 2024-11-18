---
title: CPU 스케줄링
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
      I. CPU Scheduling
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CPU 스케줄링의 정의
        </div>
        <div class="para-cntnt">
            OS가 Process의 실행을 위해 언제, 어느 CPU를 할당할 것인지의 순서를 정하는 작업
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. CPU 스케줄링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CPU 스케줄링의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/CPU-스케줄링.png" alt="CPU 스케줄링">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. CPU 스케줄링의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          종류 장중단 큐메실
  장기 스케줄링 / 큐 삽입 (long term scheduling)
    - 시작 상태의 프로세스들 중 어떠한 프로세서를 준비 큐에 삽입할 것인지를 결정
    - 시작 상태의 프로세스에게 메모리 할당을 승인할지 여부를 결정
  중기 스케줄링 / 메모리 적재 (medium term scheduling)
    - 메모리에 적재된 프로세스의 수를 동적으로 조절함
    - 프로세스를 메모리에서 디스크로 스왑 아웃시킴 -&gt; 중지상태로 변경
  단기 스케줄링 / 실행 (short term scheduler)
    - 준비상태의 프로세스 중에서 어떤 프로세스를 다음 번에 실행 상태로 만들 것인지를 결정
    - 준비 큐에 있는 여러 프로세스들 중에 어떠한 프로세스에게 CPU를 할당할 것인가를 결정
평가기준 처응반대사공
  처리량 (Throughput) - CPU가 단위 시간당 처리하는 프로세스의 개수
  응답시간 (Response time) - 대화식 시스템에서 요청 후 응답이 오기 시작할 때까지의 시간
  반환시간 (Turnaround Time) - 프로세스가 시작해서 끝날 때까지 걸리는 시간(대기시간 + 종료시간)
  대기시간 (Waiting time) - 프로세스가 준비 큐 내에서 대기하는 시간의 총합
  사용률 (CPU Utilization) - 전체 시스템 시간 중 CPU가 작업을 처리하는 시간의 비율
  공정성 보장 - 모든 사용자에게 공평한 CPU시간과 I/O 시간 할당

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
