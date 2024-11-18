---
title: OLAP
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 경영전략]
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
      I. 다차원 데이터분석, OLAP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. OLAP의 정의
        </div>
        <div class="para-cntnt">
            최종사용자가 데이터베이스에 직접접근하여 대화식 쿼리하여 분석하는 의사결정도구
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. OLAP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. OLAP의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/OLAP.png" alt="OLAP">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. OLAP의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  다차원성 / 직접접근 / 대화식분석 / 의사결정
구성요소 DDOREM 올랩큐브
  DW - 통합 데이터베이스
  DM - 제한된 주제 데이터를 추출하여 구축
  ETL/ETT - 데이터를 추출하여 DW 에 Load 시켜 정제 작업까지의 전 과정
  ODS - 운영계 시스템에서 데이터를 추출하여 ODS 에 저장
  Metadata - 요약정보, 위치 등의 정보를 저장 관리 기능
  Reporting - Reporting 및 Chart 로 결과출력
유형 비교
  유형 - ROLAP / MOLAP / HOLAP
  구조 - RDB / SQLITE / 혼합
  장점 - 사용성, 확장성 / 실시간성 / 혼합
  기술 - Snowflake 스키마 / 다차원 큐브 / Vertical, Horizontal 파티셔닝

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
