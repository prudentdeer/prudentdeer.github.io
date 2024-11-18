---
title: 로그기반회복기법
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
      I. 로그이용 데이터회복, 로그기반 회복기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 로그기반회복기법의 정의
        </div>
        <div class="para-cntnt">
            DB 변경내역을 로그에 보관, 장애발생시 REDO, UNDO를 수행하는 데이터 회복기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 로그기반회복기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 로그기반회복기법의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/로그기반회복기법.png" alt="로그기반회복기법">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 로그기반회복기법의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  부하경감 - 실시간 DB 반영에 대한 부하경감
  느린속도 - REDO, UNDO를 위하여 로그 전체 조사
유형 즉지
  즉시 갱신기법 Immediate Update
    정상동작 - 트랜잭션이 수행 중 갱신결과를 바로 로그 기록, DB Commit
    회복동작 - 트랜잭션 실패 시 로그기반 UNDO, 다중 User 환경에서는 2PL같은 보호 기술 필요
    장점 - 직관적 기록 및 회복 기술, 저장공간 적게 차지
    단점 - 로그 처리를 위한 부하 증가
  지연 갱신기법 Defered Update
    정상동작 - 트랜잭션 수행 시 로그에 우선 기록, 트랜잭션 종료 시 로그기반 DB Commit
    회복동작 - 트랜잭션이 미 종료 시 로그 폐기, 다중 User 환경에서는 2PL같은 보호 기술 필요
    장점 - 트랜잭션 완료 까지 DB 부하 적음
    단점 - REDO시 로그 기록 작업을 재 수행, 로그 검색 부하

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
