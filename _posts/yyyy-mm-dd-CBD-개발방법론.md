---
title: CBD 개발방법론
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
      I. 소프트웨어 생산성과 품질향상를 위한 CBD 개발방법론
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CBD 개발방법론의 정의
        </div>
        <div class="para-cntnt">
            독립적 컴포넌트를 개발하고 컴포넌트를 조립하여 새로운 어플리케이션을 구현하는 개발방법론
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. CBD 개발방법론
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CBD 개발방법론의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/CBD-개발방법론.png" alt="CBD 개발방법론">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. CBD 개발방법론의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  생산성, 재사용성, 변경용이성, 기술집약성, 관리용이성, 사용자 중심
개발절차
  요구 파악
    요구사항 이해 - 사용자 요구사항 수집, 도메인 분석 / 요구사항 기술서, 용어사전, 개념 모델
    요구사항 정의 - 요구사항 이해 기반, 유즈케이스 작성 / Usecase Model
  분석 및 설계
    요구사항 분석 - 객체 모델 프로토타이핑, UI 기획 / 객체 모델, UI 설계서
    아키텍처 정의 - 소프트웨어/컴포넌트 아키텍처 정의 / 아키텍처 기술서
    컴포넌트 설계 - 아키텍처 기반 I/F 명세화, 모델링 / 인터페이스 명세서, 컴포넌트 명세서
    데이터베이스 설계 - 객체 모델의 엔티티 클래스를 대상으로 DB 모델링 / ERD, DB 설계서
  구현
    개발표준 정의 - 플랫폼 특성 검토, 표준 수립 / 명명규칙, 코딩규칙, 프로그래밍가이드
    코드구현 - 플랫폼 따른 전용 Compiler 이용
  테스트
    테스트 계획 - 테스트 목표, 대상, 방법, 절차 수립 / 테스트 계획서
    테스트 수행/보고 - 테스트 수행, 절차 기록 및 승인 / 컴포넌트 테스트, 통합테스트, 인수테스트

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
