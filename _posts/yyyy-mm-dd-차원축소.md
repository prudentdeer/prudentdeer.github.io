---
title: 차원축소
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
      I. 차원의 저주 해결, 데이터 차원축소
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 차원축소의 정의
        </div>
        <div class="para-cntnt">
            차원의저주 해결위해 고차원의 데이터를 저차원의 공간으로 투영하여 차원을 축소하는 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 차원축소
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 차원축소의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/차원축소.png" alt="차원축소">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 차원축소의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 슬리퍼 슬리아
  선형
    SVD 특이값분해 - 임의의 m×n 차원의 행렬 분해 방법 Singular value Decomposition
    LDA 선형판별분석 - 클래스간 분산최대화, 클래스내 분산최소화 차원축소 Linear Discriminant Analysis
    PCA 주성분분석 - 공분산행렬 이용한 차원축소
  비선형
    SOM 자기조직화지도 - 저차원 격자에 고차원 데이터 사상
    LLE 로컬선형임베딩 - 데이터들 사이의 선형적 구조를 보존
    ISOMAP - 실제 특징을 반영하는 거리 정보를 사용
    Autoencoder - 입출력동일 잠재벡터
차원축소와 차원확장 비교
  차원 - 고차원 &gt; 저차원 &lt;&gt; 저차원 &gt; 고차원
  목적 - 복잡성감소 &lt;&gt; 모델의 표현력 향상
  기법 - PCA, LLE &lt;&gt; 커널트릭
- 정도에따라 데이터손실과 과적합 가능성 존재
차원의 저주 - 학습데이터의 수 보다 차원의 수가 많아지게 되어 모델의 성능이 떨어지는 현상

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
