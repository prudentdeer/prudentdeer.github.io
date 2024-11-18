---
title: SVM
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
      I. 초평면을 이용한 데이터의 분류, SVM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SVM의 정의
        </div>
        <div class="para-cntnt">
            데이터 간 가장 Margin이 큰 Hyperplane을 식별하는 지도학습 기반 데이터 분류 알고리즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SVM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SVM의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SVM.png" alt="SVM">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SVM의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  이상치 처리 - 데이터의 이상치가 많이 포함된 경우에도 좋은 성능 
  데이터전처리 필요 - 데이터의 스케일이나 분포 등에 민감 모델 
  선형, 비선형 분류 - 선형 SVM과 비선형 SVM으로 나뉨 
  최대마진 분류 - 과적합을 방지 구성요소 서마초커 하소
구성요소 서마초커 선비하소
  Support Vector - 분류 경계에 가장 가까운 곳에 위치한 데이터
  Kernel trick - 비선형 패턴의 데이터를 변형하여 비선형 경계면을 찾는 방법 (그림 참고)
  Margin - 분류 경계에 가장 가까운 데이터로부터 분류 경계까지의 거리
  Hyperplane - 다차원의 공간의 구분을 위한 평면
작동방식
  선형 - 커널함수 미사용 / 단순 벡터머신
  비선형 - 커널함수 사용 / 다항식커널, 유사도특성 추가
  하드마진 - 마진값을 타이트하게 잡음 / 이상치 허용하지 않음 / 과적합 발생하기 쉬움
  소프트마진 - 이상치를 어느정도 허용 / 이상치 부분 허용 
장점 - 높은 정확도 / 노이즈 강건성 / 다양한 커널함수 / 일반화성능
단점 - 파라미터튜닝 필요 / 느린 학습속도 / 대용량처리 어려움 / 이진분류 적합
SVM의 비선형 분류문제와 커널 트릭
  문제점 - 비선형 패턴은 초평면을 이용한 분류가 불가능
  해결방안 - 커널트릭 이용하여 저차원 공간을 고차원 공간으로 매핑
활용사례
  분류
    이진분류 - 스팸 필터링, 암진단, 감정분석, 사기탐지
    다중분류 - 손글씨, 숫자인식, 이미지분류
  예측
    이상치탐지 - FDS, 금융이상치, 네트워크 침입탐지
    회귀분석 - 주가예측, 시계열 예측
- 분류성능은 혼동행렬, 정확도, 재현도, 정밀도, f-1 score, ROC, AUC 이용해 평가

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
