---
title: FTS
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 컴퓨터구조]
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
      I. Graceful Degradation, 결함허용시스템
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. FTS의 정의
        </div>
        <div class="para-cntnt">
            하드웨어 혹은 소프트웨어의 결함, 오동작 발생에도 핵심기능 부분수행 가능한 시스템
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. FTS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. FTS의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/FTS.png" alt="FTS">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. FTS의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          단계별 특성 감진통복
  결함감지 - 시스템 내 결함 발생 및 내용 감지
  결함진단 - 결함의 원인/위치/파급효과 판단
  결함통제 - 결함으로 인한 오류파급 차단
  결함복구 - 결함요소 제거, 시스템 재구성
기법
  하드웨어 하레와트셀
    RAID - 디스크 미러링, 패리티 비트
    WDT - 주기적 타이머 가동을 위한 초기화, Watchdog Timer
    TMR (Triple Modular Redundancy) - 3개 이상의 프로세서가 같은 입력에 대하여 동일한 연산 수행
    SPR - 출력결과가 틀린 하드웨어는 계산과정에서 배제, Self-Purging Redundancy
    Duplication with Comparison - 2개의 프로세서를 동기 상태에서 프로세스 수행
    Stand by Sparing - 결함감지를 위한 여분의 하드웨어
  소프트웨어 소체리컨디
    Check point - 검사시점으로 되돌아가서 재수행
    Recovery Block - 같은 기능을 가진 다른 S/W 모듈을 수행
    Conversation - 정보를 교환하는 프로세서들 간에 적용 가능한 기법
    Distributed Recovery Block - Recovery Block 기법을 분산환경으로 확장
    N self-checking programming - 자가진단을 통한 컴포넌트의 결함 발견
    N version programming - N 개의 독립적인 S/W 모듈의 수행결과를 비교하여 다수의 수행결과를 채택
  데이터베이스 데롤로체그
    Rollback (Undo) - 트랜잭션 ACID 보장
    Log File 활용 회복
    Check Point
    Shadow Paging

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
