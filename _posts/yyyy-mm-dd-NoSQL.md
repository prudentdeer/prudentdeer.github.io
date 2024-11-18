---
title: NoSQL
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
      I. BASE 기반 스키마리스 DB, NoSQL
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NoSQL의 정의
        </div>
        <div class="para-cntnt">
            BASE, CAP, PACELC 이론에 기반한 확장이 가능하며 비정형데이터의 저장이 가능한 DBMS
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. NoSQL
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NoSQL의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/NoSQL.png" alt="NoSQL">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. NoSQL의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  데이터베이스 측면 스복확 비조빅
    스키마 유연성 - 스키마 변경 등 구조변경 작업이 필요할 때 재가동 없이 작업 가능
    복잡쿼리 불필요 - 조인이 불가하기 때문에 복잡한 쿼리 불필요
    확장성 - 데이터량 증가에 따른 데이터베이스 확장성을 우선적으로 지원
  데이터모델 측면
    비관계형 모델 - 데이터 간의 관계를 정의하지 않음
    조회성능 향상 - 단일 테이블을 읽어 필요한 정보를 확보
    빅데이터 처리 - 머신러닝, 실시간 대용량분석 적합
NoSQL 유형 키컬도그
  Key-Value - 데이터가 key, value pair 형태로 저장되는 유형
  Column Family - 행마다 키와 값을 저장할 때마다 각각 다른 값, 다른 스키마
  Document - key, value 형태로 저장되지만 value에 JSON, XML 이 저장
  Graph - Entity 와 관계를 저장하는 다중관계 유형
NewSQL, RDBMS, NoSQL 비교
  ACID 특성 - ACID 특성 제공 - ACID 특성 제공 - ACID 특성 미제공
  BASE 특성 - BASE 특성 제공 - BASE 특성 미제공 - BASE 특성 제공
  스키마 - Schema-less - Schema-full - Schema-less
  확장성 - Scale-out - Scale-up - Scale-out
  솔루션 - Volt DB, Spanner - Oracle, MSSQL - MongoDB, Redis
- 최근 생성AI와 데이터베이스 결합한 솔루션의 등장

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
