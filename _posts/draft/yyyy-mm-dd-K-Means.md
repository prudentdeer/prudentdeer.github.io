---
title: K-Means
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
      I. 거리기반 클러스터링, K-Means
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. K-Means의 정의
        </div>
        <div class="para-cntnt">
            K개의 Centroid 기준 최소거리 군집생성, 중심값 지속갱신하는 비지도 클러스터링 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. K-Means
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. K-Means의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/K-Means.png" alt="K-Means">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. K-Means의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          절차 초군중검
  1단계 / 초기설정 - 클러스터 개수 결정(K = n) 후 centroid 배치
  2단계 / 군집분류 - 각 데이터들을 가까운 Centroid로 할당
  3단계 / 중심점 업데이트 - 군집 학습 데이터 좌표 계산, 각 데이터 좌표들의 평균을 새로운 Centroid 갱신, 이동
  4단계 / 검증 및 완료 - 보정 후 ② ~ ③ 단계 반복, 더 이상 군집 데이터 변경이 없으면 학습 완료
구성요소 케센유클
  K - 클러스터링 개수를 결정하는 초기 파라메터
  Centroid - 각 클러스터의 중심점 역할을 하는 중심벡터
  Cluster
  유클리드거리
장점 – 수렴성이 보장 / 대용량 데이터 / 직관적 / 병렬처리가능
단점 - 클러스터의 개수를 정해야 함 / 초기값에 민감 / 이상치에 영향을 받음 / 차원의저주 가능성
- 성능평가 위해 실루엣 계수, Dunn index 사용

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
