---
title: 의사결정나무
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
      I. 트리구조기반 예측, 의사결정나무 모델
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 의사결정나무의 정의
        </div>
        <div class="para-cntnt">
            데이터를 분류하거나 예측하기위해 의사결정 규칙을 트리구조 표현하는 지도학습기반 모델
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 의사결정나무
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 의사결정나무의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/의사결정나무.png" alt="의사결정나무">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 의사결정나무의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 RPCDT BD
  Root Node - 의사결정 Tree가 시작되는 노드
  Parent Node - 주어진 마디의 상위 노드
  Child Node - 하나의 마디로부터 분리되어 나간 2개 이상의 노드
  Desicion Node - 분기가 있는 노드
  Terminal Node - 더 이상 분기가 되지 않아 자식 마디가 없는 최종 끝의 노드
  Branch - root node로부터 terminal node까지 연결된 node
  Depth - root node부터 terminal node 까지의 중간 node 들의 수
구성절차 성가최해
  성장 / ASM, Split - 분리 규칙, 정지기준
  가치치기 / Pruning, Dropout - 오분류, 복잡도, 과적합 방지
  최적화 / 교차타당성 - 이익, 위험, 비용 평가
  해석예측 / 예측모형 - 예측, 분류 활용
유형 회분
  회귀나무 / 수치형
  분류나무 / 범주형
예측모델링 예평평
  평균제곱오차, MSE - 모델 예측 값과 실제 값 간의 제곱오차의 평균 (MSE, Mean Squared Error)
    - 부모 노드의 평균 제곱 오차를 가장 많이 감소시키는 값을 기준으로 자식 노드를 생성
  평균절대오차, MAE - 모델 예측 값과 실제 값 간의 절대오차의 평균 (MAE, Mean Absolute Error)
    - 부모 노드의 평균 절대오차를 가장 많이 감소시키는 값을 기준으로 자식 노드를 생성
분류모델링 분지엔
  지니 지수 - 불순도 측정, 얼마나 다양한 데이터가 잘 섞여 있는지 정도
  엔트로피 지수 - 무질서 정도, 모델 예측 값과 실제 값 간의 절대오차의 평균
- 과적합, 일반화 극복위해 랜덤포레스트 앙상블 적용

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
