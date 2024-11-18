---
title: F1-Score
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
      I. 분석모델 정확도 평가기법, F1-Score
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. F1-Score의 정의
        </div>
        <div class="para-cntnt">
            모델의 분류성능 평가지표를 측정하기 위한 정밀도와 재현율의 조화평균 스코어
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. F1-Score
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. F1-Score의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/F1-Score.png" alt="F1-Score">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. F1-Score의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          지표도출 방법 밀재정
  Precision, 정밀도 - True 분류 중 실제 True 비율, Precision = TP / (TP + FP)
  Recall, 재현율 - 실제 True 중 True 예측 비율, Recall = TP / (TP + FN)
  Accuracy, 정확도 - Accuracy = (TP + TN) / (TP + FN + FP + TN)
분석모델 평가지표 유형 FRA
  Fall Out - 실제 False인 Data중에서 모델이 True라고 예측한 비율, FPR = FP/(TN+FP)
  ROC - 여러 임계 값들 기준으로 Recall-Fallout 변화 시각화
  AUC - ROC Curve 아래의 면적 값을 이용한 비교

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
