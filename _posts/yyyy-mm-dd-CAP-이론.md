---
title: CAP 이론
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
      I. 분산DB의 Tradeoff, CAP 이론
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CAP 이론의 정의
        </div>
        <div class="para-cntnt">
            분산DB가 갖출 수 있는 일관성, 가용성, 분할허용 중 2가지만 선택 가능하다는 이론
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. CAP 이론
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CAP 이론의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/CAP-이론.png" alt="CAP 이론">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. CAP 이론의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          CAP 설명 CAP
  일관성 (Consistency) - 모든 장비에서 동일한 데이터가 저장되어 있는 성질
  가용성 (Availablity) - 모든 서버는 클라이언트에게 항상 정상처리 응답보장
  분할허용 (Partition tolerance) - 클러스터 사이에 접속이 일부 단절되어도 동작보장
데이터베이스 유형 RDB
  CA / RDBMS / 미션 크리티컬 : 메시지 손실을 방지하는 강한 신뢰형 
  AP / Dynamo, Cassandra, Couch / 비동기서비스 : 일관성을 크게 요하지 않는 서비스에 적합
  CP / Bigtable, 몽고 DB, Redis / 대용량 분산시스템 : 데이터 보다는 성능이 중요한 퍼포먼스형        
한계
  PICK TWO 측면
    완전분리불가 - CP시스템과 완벽한 AP시스템 사이에는 수많은 가능성
    P 선택필수적 - 절대로 장애가 나지 않는 네트워크를 구성해야 하지만 그런 것은 이 세상에 존재하지 않는다. 따라서&nbsp;원하든 원하지 않든 P는 선택되어야 함
  파티션 측면  
    파티션 없는상황 - 파티션이 없는 상황을 설명하지 못함
    상충특성 존재 - 파티션이 없는 상황에서도 분산 시스템은 상충하는 특성들이 있고, 장애 상황만큼이나 정상 상황에서 시스템이 어떻게 동작하는지도 중요
CAP 이론의 한계보완 PACELC 이론
  Partition
    Available - 가용성
    Consistency - 일관성
  Else
    Latency - 지연
    Consistency - 일관성
- NoSQL 시스템들은 AP, CP 로 구성

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
