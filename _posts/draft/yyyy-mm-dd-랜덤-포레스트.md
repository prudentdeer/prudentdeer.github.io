---
title: 랜덤 포레스트
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
      I. 의사결정트리의 앙상블, Random Forest
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 랜덤 포레스트의 정의
        </div>
        <div class="para-cntnt">
            여러개의 결정트리가 Bootstrap으로 샘플링하고 개별학습 수행 후 보팅을 통해 예측결정 모델
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 랜덤 포레스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 랜덤 포레스트의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/랜덤-포레스트.png" alt="랜덤 포레스트">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 랜덤 포레스트의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징 임비노과
  임의성 - 서로 조금씩 다른 특성을 갖는 트리들로 구성
  비상관화 - 트리들의 예측들에 대한 비상관화 (decorrelation)
  노이즈 내성 - 일반화 성능의 향상 및 노이즈(noise)에 강함
  과적합 극복 - 임의화를 통한 과적합(overfitting)문제를 극복
구성요소
  의사결정트리
  부트스트래핑
  보팅
알고리즘 부트분투
  부트스트랩 샘플생성 - 부트스트랩을 통해 N개의 훈련데이터 집합 생성
  트리 생성 - N개의 기초 분류기 (트리) 훈련
  분류기 생성 - N개의 분류기 (트리) 생성
  투표 선택 - 평균 또는 과반수 투표방식
중요 매개변수 크깊임
  Forest 의 크기 - 총 forest를 몇 개의 트리로 구성할 지를 결정하는 매개변수 / 시간과 정확성 tradeoff
  최대허용 깊이 - 하나의 트리에서 루트 노드부터 종단 노드까지 최대 몇 개의 노드(테스트)를 거칠 것인지를 결정 / 오버피팅, 언더피팅
  임의성 정도 - 임의성의 정도에 따라 비상관화 수준의 결정 / 상관성

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
