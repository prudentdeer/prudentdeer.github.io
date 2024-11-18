---
title: SW 아키텍처 분석
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
      I. 소프트웨어 아키텍처 정방향 분석
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SW 아키텍처 분석의 정의
        </div>
        <div class="para-cntnt">
            프로젝트 초반에 소스코드 없이 요구사항 기반으로 ATAM, CBAM 통해 SW 구조를 분석하는 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SW 아키텍처 분석
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SW 아키텍처 분석의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SW-아키텍처-분석.png" alt="SW 아키텍처 분석">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SW 아키텍처 분석의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          설명
  - SAAM, ATAM 등 아키텍처 평가 기법 사용
  - 사전 이슈 파악 및 잠재 위험요소 분석
  - 이해관계자, 설계자, 개발자 간의 의사소통 향상
  - 세부 구현 이전에 SW를 보완하여 비용 감축
  - SW 아키텍처 분석은 주로 초기에 수행하나, 프로젝트 중에도 역방향 분석을 통해 주기적으로 구조를 평가하며
시스템 개선을 수행하는 것이 바람직
소프트웨어 아키텍처 역방향 분석
정의
  프로젝트 중에 레거시코드, 시스템 기반으로 역공학을 수행하여 SW 구조를 분석하는 기법
설명
  - 시각화 방법, 지표 방법, 관계 추출 방법 적용
  - 프로젝트 진행 중 현재/잠재적 이슈 분석
  - 컴포넌트 간 의존성/복잡성 최소화
  - 코드에 한정된 단편적인 뷰만을 제공
  - 실제 발생하는 다양한 Trade-off 반영 어려움
  - 정방향 분석과 역방향 분석을 상호보완적으로 사용하되, 분석 시 아키텍처의 철저한 평가가 필수적

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
