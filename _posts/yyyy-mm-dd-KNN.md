---
title: KNN
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
      I. 최고인접 다수결, KNN 알고리즘
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. KNN의 정의
        </div>
        <div class="para-cntnt">
            x에서 가장 가까운 k개의 원소가 많이 속하는 class로 분류하는 지도학습기반 분류 알고리즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. KNN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. KNN의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/KNN.png" alt="KNN">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. KNN의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            최고인접 다수결 기반으로 클래스 분류하는 거리기반 지도학습 분류 알고리즘
특징
  최고인접 다수결 - 기존 데이터 중 가장 유사한 k개의 데이터를 측정하여 분류
  유사도(거리) 기반 - 유클리디안 거리(Euclidian’s distance), 마할라노비스의 거리(Mahalanobis’ distance), 코사인 유사도(cosine similarity)등을 활용
  Lazy Learning 기법 - 새로운 입력 값이 들어온 후 분류시작
동작원리 핑데거매후라클
  Fingerprint DB 구축 - 특정 위치를 참조 위치로 지정, 해당 지점에서 측정 이동 객체 신호 강도 DB화
  데이터셋 그룹핑 - Fingerprint DB 내 데이터 표준 그룹화
  거리측정 - 유클리드 거리 측정
  매개변수 선택 - 데이터 분류 통해 최적 성능 k값 선택
  후보집합 생성 - 최소 거리부터 순서대로 k개 데이터 찾아 후보 집합 생성 및 정렬
  Label 값 확인 - 후보 집합의 각 원소가 어떤 클래스에 속하는지 Label 값 확인
  클래스 맵핑 - 확인한 Label값 중 가장 많은 빈도 수 차지 클래스 찾아 x를 클래스에 맵핑
장점
  효율성 - 훈련데이터에 잡음이 있는 경우에도 적용가능
  결과일관성 - 훈련데이터의 크기가 클 경우 효율적임
  간단한학습 - 모형이 단순하고 쉬운 구현 가능
단점
  성능가변성 - k값 선정에 따라 알고리즘의 성능이 좌우됨
  높은 자원요구량 - 데이터 셋 전체를 읽어서 메모리에 기억
  고비용 - 모든 훈련 샘플과의 거리를 계산하여야 하므로 연산비용이 높음
평가기법
  정확도, 정밀도, 재현율, F-1 Score
  ROC, AUC

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
