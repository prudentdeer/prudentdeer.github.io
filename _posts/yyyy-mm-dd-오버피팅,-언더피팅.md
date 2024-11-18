---
title: 오버피팅, 언더피팅
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
      I. 편향과 분산의 딜레마, 과적합 (오버피팅)
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 오버피팅, 언더피팅의 정의
        </div>
        <div class="para-cntnt">
            과도한 Feature 학습으로인해 Training 예측은 정확하지만 일반화 성능떨어지는 현상
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 오버피팅, 언더피팅
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 오버피팅, 언더피팅의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/오버피팅,-언더피팅.png" alt="오버피팅, 언더피팅">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 오버피팅, 언더피팅의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          오버피팅의 원인
  모델측면 - 편향과 분산 / 차원의 저주 / 복잡한 모델 / 부적합 알고리즘 
  데이터측면 - 부족, 품질, 쏠림
해결방안 
  모델측면 - 드롭아웃 / 정규화 / 조기종료 / 차원축소 / 앙상블
  데이터측면 - K-Fold / Bagging / Boosting / 교차검증

편향과 분산의 딜레마, 과소적합 (언더피팅)
정의
  적은 Feature 기반 학습되어 Training 데이터와 Test 데이터 모두 낮은 성능을 나타내는 현상
특징 - 저분산 고편향 
원인
  데이터 부족, 단순한 모델, 학습반복 부족
해결방안
  학습 데이터 - 충분히 많은 양의 데이터 학습
  다양한 특성 - 편향 줄이고 분산 늘려 학습
  모델 변형 - 의사결정나무, KNN, SVM 등 적용

오버피팅 언더피팅 비교
  학습성능 - 우수 &lt;&gt; 저조
  일반화성능 - 하락 &lt;&gt; 저조
  특징개수 - 많음 &lt;&gt; 부족
- 오버피팅은 고분산 저편향 경향이 존재  

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
