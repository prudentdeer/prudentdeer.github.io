---
title: New SQL
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
      I. ACID + BASE 특성을 갖춘 NewSQL 볼트DB
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. New SQL의 정의
        </div>
        <div class="para-cntnt">
            RDBMS의 ACID 특성 유지하고 NoSQL의 성능과 확장성을 제공하는 데이터베이스 관리시스템
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. New SQL
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. New SQL의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/New-SQL.png" alt="New SQL">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. New SQL의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특성
  신규 아키텍처 : 비공유 노드 클러스터를 사용, 각 노드는 데이터의 하위 집합 관리
  SQL 최적화 및 확장성 : SQL에 최적화 된 스토리지 엔진,  SQL과 동일한 인터페이스 및 확장성 제공
  투명한 샤딩 : Raft 또는 Paxos 합의 알고리즘 사용,  데이터베이스를 여러 노드로 자동 분할
주요기능 트애비 아노병
  트랜잭션
    ACID 지원 - 커밋(Commit)을 위한 필요 속성인 ACID 지원
    비잠금 동시성제어 - 기존 방식과 다른 Non-locking 구조를 지원
  아키텍처 
    노드단위 고성능 - 각 단일 DBMS 서버 노드 단위로 확장해 고성능을 보장
    병렬 아키텍처 - 병렬 아키텍처 기반 고성능 처리, 분산 처리시 데이터가 각 서버 독립적으로 존재
기술요소 인다샤 스인디
  RDBMS 측면
    인덱싱 - 데이터베이스 검색 속도 향상, 테이블 연관, 독립적인 저장공간
    MVCC - 트랜잭션의 다중 버전 동시성 제어로 트랜잭션 직렬화
    샤딩 - 동일 테이블 스키마의 데이터를 다수 데이터베이스에 분산 저장
  NoSQL 측면
    스키마리스 - 테이블과 컬럼 스키마 없이 Key-Value 기반 단순 검색, 추가 용이
    인메모리 - 고성능, 저지연 서비스, 버퍼 관리 불필요
    DB 스케일링 - scale-out 방식의 유연한 데이터 구조
NewSQL, RDBMS, NoSQL 비교
  ACID 특성 - ACID 특성 제공 - ACID 특성 제공 - ACID 특성 미제공
  BASE 특성 - BASE 특성 제공 - BASE 특성 미제공 - BASE 특성 제공
  스키마 - Schema-less - Schema-full - Schema-less
  확장성 - Scale-out - Scale-up - Scale-out
  솔루션 - Volt DB, Spanner - Oracle, MSSQL - MongoDB, Redis

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
