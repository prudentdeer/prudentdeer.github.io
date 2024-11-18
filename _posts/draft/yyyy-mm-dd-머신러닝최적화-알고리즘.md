---
title: 머신러닝최적화 알고리즘
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
      I. 효율 최적화를 위한, 머신러닝 최적화 알고리즘
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 머신러닝최적화 알고리즘의 정의
        </div>
        <div class="para-cntnt">
            머신러닝의 성능최적화위해 경사하강법, 학습률조정 통해 비용함수 최소값 탐색 알고리즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 머신러닝최적화 알고리즘
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 머신러닝최적화 알고리즘의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/머신러닝최적화-알고리즘.png" alt="머신러닝최적화 알고리즘">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 머신러닝최적화 알고리즘의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형  슴나담 아라담
  경사하강기반
    SGD - 가중치갱신 / 가중치갱신 / 지역최소점
    Momentum - 관성계수적용 / 지역최소점 해결 / 오버슈팅 가능성
    NAG - 이동점 업데이트 / 오버슈팅 해결 / 이동중지점 관리
    Nadam - Adam 개선 / 수렴이 빠름 / 튜닝 어려움
  학습률기반
    AdaGrad - 파라미터갱신 / 적응적탐색 / 학습률 0수렴
    RMSProp - 지수이동평균법 적용 / 학습률 0방지 / 노이즈 취약
    AdaDelta - Adagrad 개선 / 학습률 불필요 / 하이퍼파라미터 민감
    Adam - RMSProp와 Momentum 혼합 / 효율적최적화 / 메모리사용큼
머신러닝 최적화방안
  데이터 정규화 - 입력 데이터를 정규화
  Feature Engineering - 모델의 입력으로 사용되는 특성을 효과적으로 설계
  하이퍼파라미터 튜닝 - 교차 검증을 통해 최적의 하이퍼파라미터 조합
  앙상블 학습 - 부스팅, 배깅 기법 활용
- 예측오차를 최소화하고, 모델의 정확도를 최대화

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
