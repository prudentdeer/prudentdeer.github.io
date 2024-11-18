---
title: 자기조직화지도
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
      I. Clustering 기법, 자기조직화지도
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 자기조직화지도의 정의
        </div>
        <div class="para-cntnt">
            저차원격자에 고차원데이터 개체들이 대응하여 차원축소와 군집화를 동시수행 비지도 학습기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 자기조직화지도
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 자기조직화지도의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/자기조직화지도.png" alt="자기조직화지도">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 자기조직화지도의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  비지도 학습 (unsupervised learning)
  다차원 (multi-dimension)의 특징 벡터 (feature vectors)의 차원을 축소 (dimensionality reduction) 시켜주면서 동시에 군집화 (clustering)을 수행
자기조직화지도 과정 네반비솜가결
  네트워크 초기화 - 네트워크(Weights) 값을 Uniform Distribution으로 0.0과 1.0 사이의 랜덤 값으로 초기화
  반복 계산을 통한 클러스터링
  BMU 탐색 - 벡터에 가장 근접한 BMU(Best Matching Unit)을 맵에서 탐색
  SOM 파라미터 업데이트 - 영향력 반경(r)과 학습률(learning rate) 업데이트
  가중치벡터 업데이트 - 선택된 BMU에 대하여 영향력 반경(r) 내에 속하는 맵 내의 요소들에 대하여 Weight Vector를 업데이트
  결과생성 및 저장

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
