---
title: 분석모델 평가방법
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 인공지능]
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
      I. 분석모델 평가방법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 분석모델 평가방법의 정의
        </div>
        <div class="para-cntnt">
            데이터마이닝을 통해 생성된 모델의 에러율 예측을 통해 모델의 타당성을 평가하는 검증방법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 분석모델 평가방법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 분석모델 평가방법의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/분석모델-평가방법.png" alt="분석모델 평가방법">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 분석모델 평가방법의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          평가방법의 유형
  연속형 평가기법 연범 회결교엠 정프알아
    회귀분석 - 실제 값과 예측 값의 관계를 시각적으로 확인할 수 있는 지표
    결정계수 - 실제 값과 예측 값의 차이를 제곱한 값의 평균에 대한 실제값의 분산의 비율
    교차검증 - K-fold CV, Repeated Learning-Testing(RLT), LpOCV, LOOCV
    MSE / MAE
  범주형 평가기법
    정확도 / 정밀도 /  재현율
    F1스코어 - 정밀도와 재현율의 조화 평균
    ROC Curve - 진짜 양성 비율(TPR)에 대한 거짓 양성 비율(FPR)
    AUC - ROC 곡선 아래의 면적값, 0(최악)과 1(최선) 사이의 값

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
