---
title: 유사도
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
      I. 두 객체의 유사한 정도, 유사도
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 유사도의 정의
        </div>
        <div class="para-cntnt">
            서로 다른 두 데이터가 얼마나 같은지에 대한 정도로 분류, 측정, 군집화 등에 사용되는 지표
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 유사도
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 유사도의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/유사도.png" alt="유사도">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 유사도의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          측정방법 유마멘코자실
  유클리드 거리 / 최단거리 - 점과 점의 최단거리 계산
  마할라노비스 거리 / 맥락의 정규화 - 표본 점과 분포 사이의 거리를 측정한 값
  멘하탄 거리 - 차원별 값의 차이의 절대값을 모두 더해 계산하는 방법
  코사인 유사도 - 두 벡터간 코사인 값 유사한 정도
  자카드 유사도 - 두 집합의 합집합에서 교집합 비율을 비교하여 산출
  피어슨 유사도 - 변수 간의 상관관계와 선형성을 검토
  실루엣 계수 - 군집 내부, 외부의 거리 계산을 통해 산출
활용 클이응체
  클러스터링 / 실루엣 계수 - 군집간 거리와 효율적 분리정도 측정
  이상치 탐지 / 마할라노비스 - 다양한 출력에 적용, 분포에 제약 없음
  응집도 측정 / 코사인유사도 - 클러스터간의 응집도 측정, 다차원 거리측정 가능
  체스경로 / 맨하탄 거리 - 체스판의 거리측정에 사용

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
