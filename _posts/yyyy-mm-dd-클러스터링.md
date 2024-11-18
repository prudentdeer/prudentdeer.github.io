---
title: 클러스터링
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
      I. 유사한 데이터의 그룹화, 군집분석
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 클러스터링의 정의
        </div>
        <div class="para-cntnt">
            데이터를 유사성을 기준으로 군집화하고, 군집간 유사성과 상이성 규명하는 비지도 학습 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 클러스터링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 클러스터링의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/클러스터링.png" alt="클러스터링">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 클러스터링의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          주요 유형 설명 계비중 단장평와 KD 프
  계층적 군집분석
    최단연결법 - n * n 거리 행렬에서 거리가 가장 가까운 데이터를 묶어서 군집형성
    최장연결법 - 최단연결법과 같은 방법이나 거리가 먼 데이터나 군집을 묶어서 형성
    평균연결법 - 최단연결법으로 군집을 수행하는데 그 거리를 구하는 방식이 평균을 이용
    Ward 연결법 - 군집 내 편차들의 제곱합을 최소화하는 방식으로 군집 수행
  비계층적 군집분석
    K-Means 알고리즘 - K개의 중심값을 선정, 다른 데이터 간의 거리를 이용하여 분류를 수행하는 비지도학습
    DBSCAN 알고리즘 - epsilon, minpts 클러스터 중심 이동시키며 정해진 반경내에 밀도 기반으로 군집화를 수행하는 알고리즘
  중복 군집분석 / Patient Rule Induction Method
    프림 (PRIM) - 최소신장트리 그리디 알고리즘
군집분석의 평가기법 실엘던응
  실루엣계수 - 응집도, 분리도 평가
  Elbow method - 군집내 오차와 제곱합
  Dunn Index - 군집간거리, 군집내거리
  응집도 - 중심과 거리기반

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
