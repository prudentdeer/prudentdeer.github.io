---
title: SAD
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 소프트웨어공학]
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
      I. SAD; Software Architecture Document
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SAD의 정의
        </div>
        <div class="para-cntnt">
            SW 이해관계자들이 의사소통위해 다양한 관점에 따라 소프트웨어 아키텍처를 기술한 최종 산출물
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SAD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SAD의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SAD.png" alt="SAD">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SAD의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          목차 개배요 참설뷰기
  1. SAD 개요
    - SAD 목적 및 필요성 - SAD 구성 목차 정의, SA, SAD의중요성 및 역할 설명
    - 적용범위 - 전체 개발공정, 이해관계자 원칙, 변경관리 절차 표현
    - 이해관계자 구성 - 고객/사용자/개발팀/운영팀/QA/TA등, 의사소통 전략 제시
    - View 정의 - 아키텍쳐 표준 정의, viewpoint/concern 정의, view산출물
  2. 아키텍처 배경
    - 시스템 환경 - 목표시스템구성, Context구성, 솔루션, 개발/서버/운영환경
    - 시스템환경 제약사항 - 시스템제약사항(개발요소기술, 사용자PC환경, 기타제약)
  3. 아키텍처 요구사항
    - 품질모델 적용기준 - 적용품질모델선택, 품질속성, 시나리오, 유틸리티, 달성전략
    - 아키텍처 요구사항 - 요구사항도출, 품질속성 및 시나리오 작성
    - 영향요소 분석 - 유틸리티 트리에 의한 영향요소 분류, 설계 전략 수립
  4. 참조 아키텍처
    - 참조 viewpoint - 참조가능한 후보viewpoint(4+1view, simens -4view등)
    - 참조 아키텍처스타일 - 표준스타일 정의(Layered: Presentation, Biz-Logic, Data)
  5. 설계전략
    - 업무 컴포넌트 설계 - 도출방안, 구현방안, 정제방안
    - 공통 컴포넌트 설계 - 도출방안, 구현방안, 정제방안
    - 시스템공통기능 설계 - 공통기능정의, 인증/권한, 코드구현, 인터페이스, DB Access
  6. 시스템 뷰
    - 시스템 오버뷰 - 개발뷰에 대한 전체 요약의 누락부분 반영
    - 뷰사이의 관계 - 개발 뷰간 인터페이스 내용 및 제약사항
    - 비즈니스프로세스 뷰 - 전체조건, 제약사항, 작업흐름 뷰
    - 유즈케이스 뷰 - 전체조건, 제약사항, 유즈케이스 뷰
    - 논리 뷰 - 전체조건, 제약사항, 컨텍스트뷰, 정적/동적뷰 (분석), 논리ERD
    - 개발 뷰 - 전체조건, 제약사항, 정적/동적뷰(설계), 물리 ERD
    - 배치 뷰 - 정적/동적뷰(분석), 베포 뷰, 패키지 구조, 물리ERD
  7. 기타
    - 용어사전 - Glossary(시스템URL), Data-Dictionary
    - 참고문서 - 참고도서, 참고 표

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
