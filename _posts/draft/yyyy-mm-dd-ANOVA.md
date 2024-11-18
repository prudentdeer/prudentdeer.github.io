---
title: ANOVA
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 확률과통계]
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
      I. 분산분석, ANOVA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ANOVA의 정의
        </div>
        <div class="para-cntnt">
            서로 독립적인 집단이 셋 이상인 경우, 집단간 평균차이 확인위해 F검정 이용하는 검증방법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. ANOVA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ANOVA의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/ANOVA.png" alt="ANOVA">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. ANOVA의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 아리투리
  Oneway ANOVA - 3개 이상의 집단에 대한 평균의 차이 검정
  Repeated Measures ANOVA - 3개 이상의 시점에 대한 평균의 차이 검정 
  Twoway ANOVA - 2개의 요인에 대해 3개 이상의 집단의 평균 차이 검정
  Twoway Repeated Measures ANOVA - 2개의 요인에 대해 3개 이상의 시점의 차이에 따른 평균 차이 검정
F-test 정의
  두 모집단의 분산에 대한 차이가 통계적으로 유의한가를 판별하는 검정기법
  F-분포(표)와 F검정량(검정통계량 F)를 이용하며, Var Test 라고도 함
ANOVA, t-test 비교
  대상 - 3개집단 &lt;&gt; 2개집단
  검정통계량 - F 검정통계 &lt;&gt; T 검정통계
  제시통계량 - 평균, 표준편차, 사후검정 결과 &lt;&gt; 평균, 표준편차

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
