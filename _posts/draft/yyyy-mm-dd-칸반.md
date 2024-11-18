---
title: 칸반
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 프로젝트관리]
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
      I. 칸반보드를 통한 개발공정 가시화, Kanban
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 칸반의 정의
        </div>
        <div class="para-cntnt">
            Kanban 보드를 이용하여 Workflow를 시각화하고, 큐 관리와 WIP 제한하여 개발하는 방법론 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 칸반
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 칸반의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/칸반.png" alt="칸반">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 칸반의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  Workflow 시각화 - 담당자에게 분할된 수행업무를 카드에 기록 및 Kanban보드 게시
  WIP 제한 - Workflow 상에 동시에 진행될 수 있는 항목을 제한
  소요시간 측정 및 최적화 - 한 항목을 완료하는데 걸리는 평균시간인 사이클 타임(Cycle time)을 산정
구성요소 칸프큐싸
  Kanban Board - 업무흐름제어와 공정현황표현 / 스토리카드
  Process - 업무 수행을 통한 산출물 작성 / 업무성과
  Work Queue - 대기행렬, 개발 대기, 테스트 대기, 배포/릴리즈 대기과정 / WQL (Work Queue List)
  Total Cycle Time - 총 작업의 수행시간. 개별업무의 Cycle Time의 합으로 구성 / Total Cycle Time
스크럼 vs 칸반
  수행원리 - 반복적 개발 &lt;&gt; 연속적 개발
  공정관리 - Burn down chart &lt;&gt; WIP 제한
  작업추가 - 신규작업 추가불가 &lt;&gt; 신규작업 추가가능
  업무진행 - 하나의 Sprint 팀에서 진행 &lt;&gt; 공정마다 담당부서가 다를 수 있음

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
