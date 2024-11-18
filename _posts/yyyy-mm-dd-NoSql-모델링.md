---
title: NoSql 모델링
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
      I. 모델링 주요패턴 비집프원인
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NoSql 모델링의 정의
        </div>
        <div class="para-cntnt">
            집합 - 키값만 동일하다면 row 구조는 무관
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. NoSql 모델링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NoSql 모델링의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/NoSql-모델링.png" alt="NoSql 모델링">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. NoSql 모델링의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            프로그램 조인 - 프로그램 로직단에서 조인하는 패턴
  원자성 보장집합 - 원자성 보장위한 비정규화 패턴
  인접리스트 - 전통적 linked list 자료구조
NoSQL 모델링 절차 도쿼패기후최
  도메인모델 파악 / ERD - 도메인과 데이터, 개체와 관계 분석하고 도식화
  쿼리결과 디자인 / 디자인 모델 - 결과값을 정하여 데이터 출력 내용 기반 디자인
  패턴이용 모델링 / 데이터 모델 - Put/Get으로 표현하는 형태로 모델링
  기능 최적화 / Secondary Index - RDBMS의 Indexr개념, secondary index 이용
  후보 NoSQL 선정 / 선택 NoSql - 부하테스트, 안정성 확정성 테스트를 거친 후 선정
  최적화 및 디자인 / HW 구성도, IF 설계 - 적합한 데이터 모델 최적화, IF. 하드웨어 디자인

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
