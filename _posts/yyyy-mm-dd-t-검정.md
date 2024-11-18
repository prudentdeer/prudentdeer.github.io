---
title: t 검정
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
      I. 모평균 차이검정, t 검정
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. t 검정의 정의
        </div>
        <div class="para-cntnt">
            모집단의 분산을 모르고, 표본크기 30개이하인 모평균에 대해 평균차이를 검정하는 방법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. t 검정
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. t 검정의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/t-검정.png" alt="t 검정">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. t 검정의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          가정
  모집단의 분산 모르고, 소표본 (N &lt; 30) 
  모집단의 분포가 모두 정규분포 따른다 (정규성) 
종류 단대독
  단일표본 t 검정 / 그룹 1개 - 모평균이 특정값인지를 관측된 표본을 이용하여 검증
    - 10명의 환자에게 수면제를 투여 후, 초과 수면시간 측정
  대응표본 t 검정 / 동일그룹 시간차 - 하나의 집단내 특정사건 전후의 평균차이 비교위해 반복추출 검정기법
    - 과외를 하기 전과 후의 반 학생들의 성적 변화
  독립표본 t 검정 / 그룹 2개 - 서로 독립적인 두 집단간의 평균차이 비교위해 독립추출 검정방법
    - 성별에 따른 고등학교 2학년 학생들의 외국어 능력차이 비교연구
t 검정, z 검정 비교
  표본크기 - 작음 &lt;&gt; 큼
  모집단분산 - 모름 &lt;&gt; 알고있음
  표본평균 분포 - t-분포 &lt;&gt; 정규 분포
- 3개이상 집단간 평균차이는 ANOVA 이용

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
