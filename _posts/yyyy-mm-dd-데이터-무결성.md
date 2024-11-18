---
title: 데이터 무결성
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
      I. 데이터의 일관성 보장, 데이터 무결성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 무결성의 정의
        </div>
        <div class="para-cntnt">
            데이터의 중복이나 누락이 없는 정확성과 의미의 연속성이 보장되는 일관성이 확보된 무결상태
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 데이터 무결성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 무결성의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/데이터-무결성.png" alt="데이터 무결성">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 데이터 무결성의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          무결성 규정의 4 요소 규검제위
  규정이름 - 규정을 참조할 때 사용하는 식별자
  검사시기 - 트랜잭션 접근 유형 및 데이터와 함께 검사해야 할 시기
  제약조건 - 데이터가 만족해야 할 제약 조건
  위반조치 - 제약 조건 검사 결과 위반이 발견되었을 때 취해야 될 대응 조치
유형 개참속사키도
  개체 무결성 - 기본키는 반드시 값을 가짐, 유일성을 보장하는 최소한의 집합 / Primary Key, NOT NULL
  참조 무결성 - 외래키 속성은 참조할 수 없는 값을 지닐 수 없음
    - 입력 제약조건 - Automatic, Dependent, Null, Default, No Action 오디 널디노
    - 삭제/업데이트 제약조건 - Cascade, Ristrict, Null, Default, No Action 캐리 널디노
  속성 무결성 - 컬럼은 지정된 데이터 형식을 반드시 만족하는 값만 포함 / Character,  Date
  사용자정의 무결성 - 모든 데이터는 업무 규칙을 준수해야 함 / Trigger, User Define, Data Type
  키 무결성 - 한 릴레이션에 같은 키 값을 가진 튜플 허용 안 됨 / Primary Key, Unique Index 
  도메인 무결성 - 특정 속성값이 미리 정의된 도메인 범위에 포함 / check, default 남, 여 만 허용
강화방법 제트애프
  제약조건 - 제약 조건 기능을 선언하여 무결성을 유지
  트리거 - 트리거 이벤트시 SQL을 실행하여 무결성 조건을 실행
  애플리케이션 - 생성, 수정, 삭제 시 무결성 조건을 검증 하는 코드를 추가
  프로시져 - 저장된 SQL 문을 호출으로 수행

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
