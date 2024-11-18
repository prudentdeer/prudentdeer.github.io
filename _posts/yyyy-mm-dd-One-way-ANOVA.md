---
title: One-way ANOVA
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
      I. 일원배치 분산분석, Oneway ANOVA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. One-way ANOVA의 정의
        </div>
        <div class="para-cntnt">
            3개 이상의 표본에 대해 독립변수가 1개일 때 집단 간 종속변수의 평균차이를 비교하는 분석기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. One-way ANOVA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. One-way ANOVA의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/One-way-ANOVA.png" alt="One-way ANOVA">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. One-way ANOVA의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          조건
  독립변수 / 1개 - 이산형, 범주형 변수만 가능
  종속변수 / 1개 - 연속형 변수만 가능
수식
  Oneway ANOVA - 종속변수 (Y) = 평균(u) + 독립변수(T) + 오차(e)
  F-value = 그룹과평균까지 분산 / 그룹 내 분산
절차
  연구가설 - One-way ANOVA 방법에 적합한 연구 가설 설정
  유의수준 결정 - 귀무가설 기각 확률 설정
  가정검토 - 집단 특성 전제 조건 충족 검토(정규성, 등분산성, 독립성)
  검정통계량 - 전체 평균과 집단 평균 간 차이와 집단 평균과 개별 관찰치 차이로 구분하여 계산
    (전체 평균 – 개별 관찰값) = (전체 평균 – 집단 평균) + (집단 평균 – 개별 관찰값)
Oneway, Twoway ANOVA 비교
  목적 - 3개이상 데이터그룹 평균비교 &lt;&gt; 2개 독립변수로 3개이상 데이터그룹 평균비교
  독립변수 - 1개 &lt;&gt; 2개
  특징 - 종속변수에 대한 독립변수 3개이상 &lt;&gt; 종속변수와 서로에 대한 2개의 독립변수의 다중그룹
  샘플그룹 - 3개 이상 &lt;&gt; 각 변수에 여러 개의 샘플

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
