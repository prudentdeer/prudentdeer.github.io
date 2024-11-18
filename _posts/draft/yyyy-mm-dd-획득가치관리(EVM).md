---
title: 획득가치관리(EVM)
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
      I. 프로젝트 원가통제를 위한, EVM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 획득가치관리(EVM)의 정의
        </div>
        <div class="para-cntnt">
            완료된 작업의 가치 측정하고 계획대비 실적 분석해 향후 성과 예측하는 정량적 관리기법  
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 획득가치관리(EVM)
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 획득가치관리(EVM)의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/획득가치관리(EVM).png" alt="획득가치관리(EVM)">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 획득가치관리(EVM)의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  비용/일정관리 - 프로젝트가 다변화, 복잡화, 비용 일정관리 어려움 
  추가비용통제 - 현재 획득가치 대비 일정지연, 추가비용 통제 필요 
구성요소 측분예 
  측정요소 
    PV - 계획가치, 산정일 기준으로 각 작업 별 계획했던 작업비용을 합산한 값 
    EV - 획득가치, = BAC * 진행률, 현재까지 완료된 성과에 대한 계획된 비용 
    AC - 실제원가, 산정일 기준으로 각 작업 별 실제 소요비용을 합산한 값 
    BAC - 완료시점 예산, 전체 프로젝트에 할당된 예산 Budget At Completion 
  분석요소 
    SV - 일정 차이, = EV - PV, 계획대비 일정 편차 분석 (SV &gt; 0 : 양호, SV = 0 : 준수, SV &lt; 0 : 지연) 
    CV - 원가 차이, = EV - AC, 예산 초과했는지 분석 (CV &gt; 0 : 양호, CV = 0 : 준수, CV &lt; 0 : 초과) 
    SPI - 일정 성과지수, = EV / PV, 일정대비 효율적으로 성과를 냈는지 일정차이 분석 (SPI &gt; 1 : 양호, SPI = 1 : 준수, SPI &lt; 1 : 지연) 
    CPI - 원가 성과지표, = EV / AC, 실제 원가지출의 효율성 측정지수 (CPI &gt; 1 : 양호, CPI = 1 : 준수, CPI &lt; 1 : 초과) 
  예측요소 
    BCWR - 남은 업무, = BAC – EV, BAC 에서 현재 기준일까지 완료된 실시간성을 감한 금액 Bugeted Cost for Work Remained
    ! ETC - 잔여분 산정치, = BAC – EV / CPI, 현재까지 나타난 CPI를 반영하여 프로젝트 종료 시까지 유효하다고 판단하여 계산함 Estimate To Completion 
    ! EAC - 완료 최종예산 = AC + ETC, 현시점에서 예측 종료 발생 원가 Estimate At Completion 
    ! VAC - 완료 비용편차 = BAC - EAC, 종료 시 추가 발생 원가 추정치, Variance at Completion
* 문제풀이시 결론을 맺어주면 좋음, 자원이 남고 일정은 부족하니 Crashing 사용고려

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
