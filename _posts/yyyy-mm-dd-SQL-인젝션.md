---
title: SQL 인젝션
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 보안]
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
      I. SQL Query 변경, SQL-Injection
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SQL 인젝션의 정의
        </div>
        <div class="para-cntnt">
            파라메터 변조 후 쿼리에 삽입하여 재구성하거나 비정상 DB 접근을 시도하여 공격하는 해킹 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SQL 인젝션
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SQL 인젝션의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SQL-인젝션.png" alt="SQL 인젝션">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SQL 인젝션의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  대량삽입, 자동스크립트
유형 에블유스
  Error-Based - 에러 메세지를 이용한 공격방식
  Blind SQL Injection - 쿼리조건에 따른 결과화면의 차이를 이용한 공격방식
  Union - 추가적 쿼리 삽입하여 인젝션
  Stored Procedure - 프로시저에 악성코드 삽입
공격기법 인권시데
  인증우회 - 인증을 처리하는 모듈이 입력 값에 대해 적절히 검사하지 않았을 경우
  권한상승 - 공격자가 DB의 시스템 권한을 획득
  시스템 에러이용 - 에러메시지를 통하여 정보 얻기
  데이터의 열람/조작 - Error-Based Injection, Blind SQL Injection 등의 기법을 통해 주요 데이터의 조회, 테이블 생성등
조치기법 - JAVA 기준
  Stored Procedure - SQL Query문은 DBMS의 내부 프로시저에 구현, 웹 프로그램에서는 변수 값들을 프로시저에 전달
  PreparedStatement - 기본제공 클래스를 활용, ASP는 ADO Command 객체를 활용
대응방안
  입력값 검증 - 데이터타입, 길이제한, / 치환
  웹 방화벽 - 패턴기반 sql 인젝션 차단
  Prepared Statement - DBMS 드라이버 이용
  에러 미출력 - 에러 노출 차단

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
