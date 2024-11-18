---
title: 클래스 불균형
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
      I. Accuracy Paradox, 클래스 불균형
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 클래스 불균형의 정의
        </div>
        <div class="para-cntnt">
            학습데이터의 클래스 변수가 균일하지 않고 치우쳐서 편향된 모델을 학습하게되는 불균형 현상
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 클래스 불균형
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 클래스 불균형의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/클래스-불균형.png" alt="클래스 불균형">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 클래스 불균형의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          해결방안 언오리스
  언더 샘플링 - 비율이 큰 클래스를 작게 함
  오버 샘플링 - 데이터 복사, 비율이 작은 클래스를 키움
  리 샘플링 - 다시 비율조정해 샘플링
  SMOTE - KNN 이용 유사데이터 생성기법
클래스분류 평가지표
  F1 score - 정밀도와 재현율 조화평균
  ROC curve - FPR, TPR 커브
  AUC - ROC의 하단면적

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
