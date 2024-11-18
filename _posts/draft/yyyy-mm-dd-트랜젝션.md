---
title: 트랜젝션
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
      I. DB의 논리적 작업단위, 트랜잭션
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 트랜젝션의 정의
        </div>
        <div class="para-cntnt">
            데이터베이스의 상태를 변환시키는 논리적 기능을 수행하는 DB의 최소 작업단위
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 트랜젝션
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 트랜젝션의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/트랜젝션.png" alt="트랜젝션">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 트랜젝션의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          연산
  Commit - 트랜젝션 성공시 로그저장
  Rollback - 트랜젝션 비정상종료, 재시작 or 취소
특징 ACID
  Atomicity / All or Nothing - 트랜젝션 내 연산이 모두 처리되거나 안되거나
  Consistency / 무결성 - 트랜잭션 수행 전후 각각 일관성이 보장되는 서로 다른 상태가 된다
  Isolation / 독립수행 - 트랜잭션간 독립적으로 실행되어야 함
  Durability / 결과영속 - 결과는 영구적으로 데이터베이스에 저장
상태전이 활부완 실철종
  시작
    활동상태 - 초기 상태, 트랜잭션이 실행 중이면 동작 상태
  완료
    부분완료상태 - 마지막 명령문이 실행된 후에 가지는 상태
    완료상태 - 트랜잭션이 성공적으로 Commit 된 후 가지는 상태
  실패
    실패상태 - 정상작인 실행이 더 이상 진행 될 수 없을 때 가지는 상태
    철회상태 - 트랜잭션이 취소, 트랜잭션 시작 전 상태로 Rollback 상태
  종료
    종료상태 - 커밋되거나 중단된 후 마지막 및 최종 트랜잭션 상태
ACID 와 BASE 의 비교
  적용분야 - RDBMS &lt;&gt; NoSQL
  범위 - 트랜젝션 한정 &lt;&gt; 시스템 전체
  중점 - Commit 집중 &lt;&gt; 가용성
  시스템 - 엄격한관리 &lt;&gt; 성능에 초점
  효율성 - 테이블 디자인 &lt;&gt; 쿼리 디자인
- UNDO, REDO 정책에따라 트랜젝션 영향

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
