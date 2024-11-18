---
title: IMDG
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
      I. 물리적 분산 메모리의 논리적 통합, IMDG
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IMDG의 정의
        </div>
        <div class="para-cntnt">
            대용량 데이터 관리위해 메모리를 클러스터링해 저장소로 활용하는 분산 메모리 시스템
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IMDG
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IMDG의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IMDG.png" alt="IMDG">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IMDG의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          주요기술 키콜이락 클레싱
  데이터처리
    Key-Value - 키(Key) 기반 데이터 분산 저장
    Collection API - 다수 노드 대상 HashMap, HashSet 사용
  트랜잭션 기술
    Distributed Event - Publish 순서 보장 Topic 읽기 가능한 분산 메시지 큐
    Distributed Lock - 다수 분산 시스템에서 단일 Lock 기반 동기화
    Transactions - 신뢰성 확보를 위한 Commit/Rollback
    Off-heap Memory - Full GC 처리시간 향상을 위한 JVM 메모리
  분산 기술
    Clustering - 다수 서버 메모리를 단일 메모리 저장소로 구성
    Replication - 다수 서버에 데이터 분산하여 데이터 유실방지/복구기능
    Synchronize - 사용자 요청은 다수 서버에서 병렬 처리
IMDG, RDBMS, NOSQL
  Scale Out        O        x        O
  Availability      O        x        O
  Consistency    O        O        X        
  In-Memory      O        O        X

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
