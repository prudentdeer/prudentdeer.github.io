---
title: 비지도학습
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
      I. 비지도학습
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 비지도학습의 정의
        </div>
        <div class="para-cntnt">
            입력 값에 대한 정답이 주어지지 않으며, 데이터의 패턴, 상관관계를 알아내는 기계학습
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 비지도학습
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 비지도학습의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/비지도학습.png" alt="비지도학습">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 비지도학습의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 거밀전모
  군집화
    거리기반 - 중심값과의 최소거리 기반 군집 형성 / 군집 수 선정 → 좌표 계산 → 중심값이동(반복)
    밀도기반 - 군집을 이루는 벡터 밀도 기반 군집 형성 / 군집 벡터 수 선정 → 반경 내 군집 → 중심벡터 변경(반복)
  패턴인식
    전처리 / 특징 추출 - 표본화, 정규화, 노이즈 제거, 주성분 분석, 데이터 마이닝
    모델 선택 / 인식 - Bagging/Boosting, 앙상블 학습, 혼동 행렬, ROC Curve, AUC, FP Rate
기법
  군집기반 비지도학습 K군계 자주독
    K-Means - 군집별 중심값에서 데이터의 거리를 측정
    Clustering / 군집화 - 밀접하게 관련된 데이터들의 그룹을 찾는 기법
    HCA / 계층군집분석 - 전체 데이터를 계층 구조로 분할, 다차원 데이터의 시각화에 유용
  차원축소기반 비지도학습
    자기조직지도 (SOM) - 대뇌피질의 시각피질을 모델화한 인공신경망의 일종으로 비지도 학습에 의한 클러스터링 방법
    주성분 분석 (PCA) - 분포된 데이터들의 주성분을 가장 잘 표현할 수 있는 벡터를 찾는 기법
    독립성분 분석 (ICA) - 다변량의 신호를 통계적으로 독립적인 하부 성분으로 분리하는 계산 방법

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
