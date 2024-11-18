---
title: SW 아키텍처 평가
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 소프트웨어공학]
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
      I. 아키텍처 검증 방법론, 소프트웨어 아키텍처 평가
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SW 아키텍처 평가의 정의
        </div>
        <div class="para-cntnt">
            아키텍처 접근법이 품질속성에 미치는 영향을 판단하고, 아키텍처 적합성을 평가하는 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SW 아키텍처 평가
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SW 아키텍처 평가의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SW-아키텍처-평가.png" alt="SW 아키텍처 평가">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SW 아키텍처 평가의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          평가모델 시설 사세아(SACE AA)
  시나리오 기반
    SAAM - 수정 용이성과 기능 분석 중심 / Software Architecture Analysis Method
    ATAM - Trade-off, 성능, 가용성 / Architecture Tradeoff Analysis Method
    CBAM - ATAM 에서 부족한 경제적 평가 보강 / Cost Benefit Analysis Method
    EATAM - 개별 평가모델의 확장, PL 기반 / Extending
  설계 기반 
    ADR - 구성요소간 응집도 평가, 실습적용, 디자인기반 / Active Design Review
    ARID - 혼합방식, 부분 아키텍처 초기 평가 / Architecture Review for intermediate Design
평가기법 시뮬수경 예실정사
  Scenario / 예측평가 - 미리 정의된 Profile에 의존하여 평가
  Simulation / 실무평가 - BMT 시뮬레이션 기반 평가
  Mathematical / 정량평가 - 모델 수치화 수학적 기반 모델
  Experience / 사례평가 - 적용하는 경험 기반의 평가

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
