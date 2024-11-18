---
title: MVCC
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
      I. 무결성과 직렬성 보장, 다중버전 동시성 제어
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MVCC의 정의
        </div>
        <div class="para-cntnt">
            하나의 트랜잭션에서 데이터 다중버전 상태 중 버전에 맞는 CR BLOCK을 처리하는 동시성제어기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MVCC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MVCC의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MVCC.png" alt="MVCC">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MVCC의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          동작절차
  Step 1 - SCN 10023번 시점 트랜젝션 시작된 쿼리가
  Step 2 - SCN 10023번 이후 변경된 데이터 만나면 
  Step 3 - Rollback Segment, Undo 영역의 CR Copy 참고해서
  Step 4 - SCN 10023을 넘지 않는 데이터 중 최신 데이터를 읽음
구성요소 CCRS
  CR Copy - Undo 영역에 저장된 정보를 이용해 트랜잭션 시작 시점의 일관성 있는 버전을 읽어 복사
  CR Block - CR Copy를 이용하여 가져온 값을 저장하는 Block
  Rollback Segment - 이전 버전을 보관하는 별도의 저장소
  SCN (System Change Number) - Select 수행시 갖는 고유한 번호
유형
  Multiversion Timestamp Ordering
    - BMS에서 생성하는 고유번호인 타임스탬프를 시간 순서에 따라 트랜잭션에 부여하여 동시성 제어의 기준으로 사용하는 기법
  Multiversion Two-Phase Locking 
    - 하나의 데이터 항목에 R(읽기), W(쓰기), (보증)의 세 가지 잠금 모드를 사용함,  세 가지 락은 유기적으로 서로 확인

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
