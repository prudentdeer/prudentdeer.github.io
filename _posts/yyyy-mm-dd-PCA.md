---
title: PCA
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
      I. 차원 축소를 통한 주성분 분석 알고리즘, PCA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. PCA의 정의
        </div>
        <div class="para-cntnt">
            데이터를 가장 큰 분산을 가진 주성분으로 차원축소하여 정보손실 최소화 차원축소 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. PCA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. PCA의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/PCA.png" alt="PCA">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. PCA의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  공분산 행렬 - 확률변수들의 관계를 나타내는 행렬 (cov-var matrix)
  고유 값 분해 (EVD) - 어떠한 행렬 A를 A의 직교 고유벡터(Orthogonal Eigenvector)와 고유값(Elgenvalue)의 곱의 합으로 분해
  직교 변환 - 고차원 공간의 표본들을 선형 연관성이 없는 저차원 공간(주성분)의 표본으로 직교 변환
프로세스 데공고피
  데이터 표준화 / Standard Scaling - 표준집합에 대한 스케일링 적용
  공분산행렬 생성 / n x n 대칭행렬 - 공분산 2 개의 특성간의 상관정도를 나타냄
  고유벡터계산 / 고유값선택 - 고유벡터(주성분)의 부분집합 k개 선택
  피처변환 / n X k 변환행렬 - 데이터셋은 고유백터 matrix 와 내적하여 n에서 k 차원으로 차원축소
응용사례
  얼굴인식
  지문인식
https://ddongwon.tistory.com/114

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
