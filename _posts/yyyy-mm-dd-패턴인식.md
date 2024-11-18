---
title: 패턴인식
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
      I. 사물 인식 기술, 패턴인식
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 패턴인식의 정의
        </div>
        <div class="para-cntnt">
            문자, 물체 등을 인식하기 위해 표준 패턴과 입력 패턴 비교 기반 사물 식별 및 클래스 구분 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 패턴인식
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 패턴인식의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/패턴인식.png" alt="패턴인식">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 패턴인식의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          프로세스 수특모인
  수집, 전처리 / 표본화, 정규화, Noise 제거 : 실세계 사물, Data 센싱
  특징 추출 / 분류, 회귀, 클러스터링 : 지도/비지도 학습 기반
  모델 선택 / 교차 검증 : Bootstrap, K-fold Cross Validation, Bagging, Boosting, 앙상블
  인식 단계 / 클래스 분류, 혼동 행렬        : ROC Curve, AUC, FP Rate, Euclidean, Youden Index
패턴인식 접근법 통신템구
  통계적 접근법 / 확률밀도 함수 : 패턴집합 통계적 생성
  신경망 접근법 / CNN, SVM : 입력층, 은닉층, 출력층
  템플릿 정합법 / 패턴 정규화 : 유클리디언기법, 템플릿 사전 준비
  구조적 접근법 / 패턴 구조화 : 구조적 유사성 조사/분류

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
