---
title: 분산 DB
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
      I. 고가용성 위한 분산 데이터베이스
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 분산 DB의 정의
        </div>
        <div class="para-cntnt">
            물리적으로는 분산화된 형태지만 논리적으로 하나의 시스템으로 관리되는 데이터베이스
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 분산 DB
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 분산 DB의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/분산-DB.png" alt="분산 DB">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 분산 DB의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          목적
  데이터처리 지역화, 운영 및 관리의 지역화, 처리/부하분산 및 병렬처리, 데이터 가용성 신뢰성 향상
유형 위수직복요
  위치분산 - 자재 DB, 파트너 DB, 부서 DB / 생산 DB, 판매 DB, 직원 DB
  수평분할 - 최근 7일을 제외 / 최근 7일 
  수직분할 - 제품 번호, 생산 원가 / 제품 번호, 재고량, 판매가
  복제 - 지사 판매제품만 부분복제 / 본사의 제품 DB를 전체복제
  요약 - 지사 실적 DB 분석결과 / 실적 DB를 통합한 DB
투명성 위복병분장
  위치 투명성 / 논리엑세스 - 실제위치 필요없이 논리적 명칭만으로 액세스
  복제 투명성 / Replica - DB 객체가 여러 site에 중복 되어 있는지 알 필요가 없는 성질
  병행 투명성 / Time Stamp, 2PL - 다수 트랜잭션 동시 수행시 결과의 일관성 유지 
  분할 투명성 / 단편화 - 하나의 논리적 Relation이 여러 단편으로 분할되어 각 단편의 사본이 여러 site에 저장
  장애 투명성 / 무결성유지 - 구성요소(DBMS 등)의 장애에 무관한 트랜잭션의 원자성 유지
- DRS 구성시에도 분산 DB 아키텍처 이용

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
