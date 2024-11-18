---
title: 추정
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
      I. 추정
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 추정의 정의
        </div>
        <div class="para-cntnt">
            모집단에서 추출한 표본 특성에 기초하여, 미지의 모수에 대해 추측/추론을 하는 추론 과정
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 추정
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 추정의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/추정.png" alt="추정">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 추정의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          추정량 조건 불효일충
  불편성 - 추정량 기대값과 실제 모수와의 차인 편의(bias)가 없는 기대값과 모수가 동일한 추정량
  효율성 - 불편추정량 중 분산이 적을수록 효율적인 성질
  일치성 - 표본이 클수록 추정량이 모수에 근접하는 성질
  충분성 - 모집단의 모수에 대한 정보를 더 많이 제공하는 성질
대표적 추정기법
  점추정 - 표본을 기반으로 모수 추정치를 추론하여 하나의 숫자, 점으로 나타내는 추정기법
  구간추정 - 표본을 기반으로 모수 추정치를 추론하여 신뢰구간, 범위로 나타내는 추정기법
점추정, 구간추정 비교
  목적 - 단일값 추정 &lt;&gt; 범위 추정
  형태 - 점 &lt;&gt; 상하한값
  표현 - 추정값 &lt;&gt; 신뢰구간
  불확실성 - 미고려 &lt;&gt; 고려
  정보의 양 - 제한된 정보 &lt;&gt; 추가 정보 제공
  사용용이성 - 간단하고 해석 용이 &lt;&gt; 계산 복잡, 해석 용이
추정기법 자적우사베
  최소자승법 - 평균제곱오차가 최소가 되도록 (최소 평균제곱오차) 추정량을 만드는 것
  적률법, MME - 모집단 확률분포를 알지 못해도, 모집단 적률에 대한 추정량을 구할 수 있는 방법
  최대우도법, MLE - 특정 확률분포를 가정하여, 그때 최대우도를 보이는 추정량을 구하는 법
  최대사후확률 판정법, MAP - 사후확률을 최대화시키는 부류로 추정 분류하는 결정규칙
  베이즈 추정법 - 데이터 수가 적어도 추측가능하고, 데이터 수가 많아질수록 정확해짐

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
