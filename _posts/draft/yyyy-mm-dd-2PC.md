---
title: 2PC
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
      I. 2 Phase Commit
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 2PC의 정의
        </div>
        <div class="para-cntnt">
            분산 데이터베이스 환경 원자성 보장위해 Prepare, Commit 2단계 수행하는 매커니즘 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 2PC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 2PC의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/2PC.png" alt="2PC">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 2PC의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          절차 
  Prepare 
    - 응용 프로그램은 DB의 갱신 처리 마지막 단계에서 COMMIT 명령
    - 커미트 명령을 접수한 마스터 컴퓨터는 갱신 대상의 모든 서버에 대해서 PREPARE 지시
    - 데이터를 갱신할 준비가 되어 있으면 READY 응답
  Commit
    - 모든 서버 READY시 각 서버에 COMMIT 지시
    - 각 서버는 디스크 데이터를 갱신
    - 한 대의 서버에서도 처리에 이상이 있으면 모든 서버에 ROLLBACK 명령
구성
  Coordinator
  Local coordinator
  Participant
  Commit point site (commit/rollback수행 노드)
  Client (다른 DB 이용 노드) 
한계점
  신뢰성측면(노드 장애)
  상호호환성 측면(매커니즘 상이 구현어려움)
3PC, NPC
  단계1: 조정자가 Prepare 메시지를 보내고, 각 사이트의 트랜잭션 매니저는 실행완료 혹은 Abort 수행
  단계2: 조정자가 트랜잭션을 완료 혹은 취소 결정
[데이터베이스 시스템] P510~546

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
