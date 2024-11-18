---
title: 데이터 레이크하우스
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 데이터베이스]
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
      I. 웨어하우스와 레이크 장점 결합, Data Lakehouse
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 레이크하우스의 정의
        </div>
        <div class="para-cntnt">
            데이터레이크의 확장성과 웨어하우스의 구조관리기능 결합한 하이브리드 데이터관리 아키텍처
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 데이터 레이크하우스
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 레이크하우스의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/데이터-레이크하우스.png" alt="데이터 레이크하우스">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 데이터 레이크하우스의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          데이터 처리
  Batch Processing - 일괄 배치 단위 정형, 비정형 데이터 통합 수집 및 적재 수행
  Streaming Processing - CDC, CEP 기반 실시간성 제공 데이터 수집, 변환, 전달 구성
데이터 저장
  ACID 트랜잭션 - 원자성, 일관성, 고립성, 영속성 기반 데이터 정확성 관리
  데이터 파이프라인 - 데이터 옵스 기반 데이터 플랫폼, 아키텍처 구성 제반 인프라
  스키마 레지스트리 - 생산 데이터 구조, 포맷, 변경 히스토리 관리 및 통제 수행
데이터 서빙
  Open API - REST, gRPC 및 JDBC, ODBC Driver 기반 연동 인터페이스
  BI 도구, 대시보드 - 데이터 시각화, 비즈니스 의사 결정 지원 목적 분석 도구

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
