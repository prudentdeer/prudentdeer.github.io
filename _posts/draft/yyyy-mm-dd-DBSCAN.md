---
title: DBSCAN
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
      I. 밀도기반 클러스터링, DBSCAN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DBSCAN의 정의
        </div>
        <div class="para-cntnt">
            Epsilon 반경 내 Minpts 이상 군집화 connected 연결 밀도기반 클러스터링 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DBSCAN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DBSCAN의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DBSCAN.png" alt="DBSCAN">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DBSCAN의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          절차 초군노군
  초기설정 - epsilon 및 minPts 의 설정
  군집생성 - 임의 점에서 엡실론 반경 내 minPts 개수 만족 시 군집화
  Noise 분류 - 임의 점에서 엡실론반경 내 미 존재 시 Noise로 분류
  군집완성 - 각 점에서 엡실론 반경 내 minPts 충족하는 객체집합(군집) 완성
구성요소 코보노 커엡민
  Core Point - 군집화 가능한 포인트
  Border Point - 클러스터를 구성하는 포인트
  Noise Point - 클러스터에 속하지 못하는 포인트
  Connected - 한 클러스터내 2개의 corepoint 존재시 하나로 인식
  Epsilon - 클러스터 인식반경
  MinPts - Epsilon 반경 내 군집 위해 필요한 객체 수
장점 - 비선형 클러스터링 가능함 / 군집개수 지정 필요없음 / 노이즈 강건성 / 범주형 처리가능
단점 - 입력순서에 따른 군집결과 상이 / 고차원 데이터 불가능
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
