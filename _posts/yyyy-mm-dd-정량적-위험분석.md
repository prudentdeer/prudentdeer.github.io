---
title: 정량적 위험분석
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
      I. 프로젝트 위험의 수치화, 정량적 위험분석
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 정량적 위험분석의 정의
        </div>
        <div class="para-cntnt">
            위험에 대응하기위해 위험요인을 수치화 계산하여 프로젝트 위험을 정량화하는 분석기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 정량적 위험분석
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 정량적 위험분석의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/정량적-위험분석.png" alt="정량적 위험분석">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 정량적 위험분석의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          필요성
  빠른변화대응 / 불확실성 증가 / 복잡성 증가
  위험 정량화 / 부정요소 통제 / 비즈니스 연속성
분석기법 민의몬과 이확수확
  데이터 분석
    민감도 분석 - 다른 위험 수치는 고정시킨 상태에서 임의의 한 위험을 변동
    의사결정나무 - 각 의사 결정에 따른 기대값을 계산하여 최적의 의사결정 선택
    몬테카를로 - 난수표 생성, 여러 번의 모의 프로젝트를 수행
    과거자료 분석 - 과거자료 통한 위험발생 가능성 예측, 데이터 수량에 따른 정확도
  수학적 접근법
    EMV - 발생확률 X 가치, &gt; 0 : 기회, &lt; 0 : 위협 (Expected Monetary Value)
    확률지배 - 손실위험의 위험성의 증가가 최적손실통제에 주는 영향을 분석
    수학공식 - 위협발생빈도를 계산하는 식을 이용하여 위험을 계량화
    확률분포법 - 확률적으로 편차를 이용하여 최저,보통, 최고 위험평가를 예측

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
