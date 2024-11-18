---
title: ARIES
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
      I. 빠른 데이터베이스 복구 위한 ARIES 회복 알고리즘
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ARIES의 정의
        </div>
        <div class="para-cntnt">
            DB 장애 발생시 WAL (로그선행기법) 통해 기록된 LSN (로그순차번호) 이용한 회복기법 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. ARIES
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ARIES의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/ARIES.png" alt="ARIES">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. ARIES의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  로그순번 기록, 논리/물리적 REDO 연산, 연산 최적화 
프로세스 분리언
  1단계 / 분석단계 - REDO 가 시작되어야 하는 로그의 위치를 결정
  2단계 / REDO 단계 - REDO 시작 위치의 로그로부터 끝날 때 까지 REDO 를 수행
  3단계 / UNDO 단계 - 로그를 역순으로 읽으면서 진행 트랜잭션의 연산을 역순으로 UNDO
필요요소 LTD
  Log - write, commit, abort, end 시 기록, 각 로그 레코드마다 로그 순차번호(LSN)가 할당 / LSN 할당
  Transaction Table - 진행 트랜잭션에 대한 정보 / 트랜잭션 정보
  Dirty Page Table - 버퍼에 있는 오손 페이지에 대한 정보 / Dirty page 정보
ARIES 구성요소 WLRL
  WAL (Write Ahead Logging) - DB 변경 사항에 대한 전체 로깅
  LSN (Log Sequence Number) - 모든 로그에 대한 고유 순서 번호
  Repeating History - 장애 시 이전의 데이터베이스 수행 기록을 모두 추적하여 REDO
  Logging Changes - UNDO 완료된 트랙잭션을 기록하여 UNDO 반복 수행 회피

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
