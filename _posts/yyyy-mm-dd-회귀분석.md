---
title: 회귀분석
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
      I. 회귀분석
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 회귀분석의 정의
        </div>
        <div class="para-cntnt">
            하나 또는 그 이상의 독립변수들이 종속변수에 미치는 영향을 추정할 수 있는 통계 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 회귀분석
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 회귀분석의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/회귀분석.png" alt="회귀분석">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 회귀분석의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형
  다중회귀분석 - 여러 개의 요인이 하나의 종속변수에 대해 미치는 영향을 분석, 종속변수가 연속변수임
  조절회귀분석 -  독립변수들이 종속변수에 미치는 영향에 대해 조절적인 역할을 하는 요인에 대한 분석
  로지스틱 회귀분석 - 여러 개의 요인이 하나의 종속변수에 대해 미치는 영향을 분석, 종속변수가 명목변수임(가부, Y/N, 불량/양호 등)
  구조방정식 모델 - 독립변수들이 종속변수에 미치는 영향을 분석하지만, 직접적으로 영향을 미치지 않으며 중간에 매개변수들이 있는 현실을 반영한 분석 방법
변수선택방법 전후단
  전진선택법 - 모형적합에 가장 큰 영향있는 독립변수 추가하는 방식
  후진제거법 - 모형적합에 가장 영향력 약한 독립변수를 제거하는 방식
  단계적방법 - 전진 + 후진, 독립변수추가 &gt; 독립변수제거

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
