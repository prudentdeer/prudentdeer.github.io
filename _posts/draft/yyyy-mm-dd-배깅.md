---
title: 배깅
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
      I. 배깅의 개요 = Bootstrap + Aggregating
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 배깅의 정의
        </div>
        <div class="para-cntnt">
            데이터에서 여러번의 bootstrap 샘플링 후 각 모델을 결합해 최종 예측모형을 만드는 알고리즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 배깅
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 배깅의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/배깅.png" alt="배깅">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 배깅의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징 분다오결
  분산 최소화 - 편향이 낮은 모델들을 이용한 분산 최소화
  다양성 - 각 모델별 알고리즘이 다를 수 있음
  오버피팅 방지 - 과적합된 모형, 편향이 작고 분산이 큰 모형에 적합
  결측치 우수
절차
  1) Row data에서 bootstrap 데이터 추출
  2) 추출을 반복하여 n개의 데이터 생성
  3) 각 데이터를 각각 모델링 하여 모델 생성
  4) 단일 모델을 결합하여 배깅 모델 생성

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
