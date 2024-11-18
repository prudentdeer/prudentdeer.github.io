---
title: 고립성 레벨
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
      I. ACID 속성 보장을 위한, Isolation Level
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 고립성 레벨의 정의
        </div>
        <div class="para-cntnt">
            트랜잭션 실행 중 다른 트랜잭션 접근 불가하도록 고립성을 유지하기 위한 데이터허용 수준
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 고립성 레벨
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 고립성 레벨의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/고립성-레벨.png" alt="고립성 레벨">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 고립성 레벨의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  ANSI/ISO SQL Standard - SQL 92 표준에서 4단계로 표준화, DBMS 벤더들이 준수
  ACID 보장 - 트랜잭션의 속성인 ACID를 만족하기 위한 설정
  Locking 기반 - 각각의 설정은 Locking 기술을 기반으로 Isolation Level을 조정
구성요소 고일저병 언커리시
  0 Level / Read Uncommitted - 갱신중 데이터 읽기허용
  1 Level / Read Committed - 갱신중 데이터 읽기제한
  2 Level / Repeatable Read - 데이터 읽을 때, 종료 시까지 갱신/삭제 제한
  3 Level / Serializable Read - 데이터 영역 순차적 읽을 때, 영역 전체에 접근제한
불충분한 격리에 따른 읽기 이상현상
  Dirty Read - 연산 중이던 트랜잭션이 롤백 될 경우 데이터를 읽어간 트랜잭션이 갖게 되는 데이터의 일관성을 보장 불가
  No Repeatable Read - 한 트랜잭션이 동일한 데이터에 대한 읽기를 반복적으로 수행할 때 다른 트랜잭션이 해당 데이터를 변경 가능
  Phantom Read - 트랜잭션이 일정 영역의 데이터를 순차적으로 읽을 때, 다른 트랜잭션이 해당 데이터 영역에 데이터 삽입/삭제 가능

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
