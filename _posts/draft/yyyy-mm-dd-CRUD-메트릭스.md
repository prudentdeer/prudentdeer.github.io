---
title: CRUD 메트릭스
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
      I. 프로세스와 데이터간의 상관관계, CRUD Matrix
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CRUD 메트릭스의 정의
        </div>
        <div class="para-cntnt">
            시스템 개발 시 프로세스와 DB에 저장되는 데이터 사이의 Dependency를 나타내기 위한 매트릭스
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. CRUD 메트릭스
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CRUD 메트릭스의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/CRUD-메트릭스.png" alt="CRUD 메트릭스">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. CRUD 메트릭스의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          작성절차
  데이터 모델링
  ERD 분석 및 작성
  업무 기능 분해도 작성 
  CRUD 매트릭스 작성
표현방법
  C / Create - 하나의 업무 기능이 데이터를 생성하는 관계
  R / Read - 하나의 업무 기능이 업무 수행의 목적을 달성하기 위해서 데이터를 참조하는 관계
  U / Update - 하나의 업무를 수행하는 과정에서 데이터가 수정/갱신되는 관계
  D / Delete - 하나의 업무를 수행하는 과정에서 데이터가 삭제되는 관계

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
