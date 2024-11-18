---
title: TDD
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
      I. 테스트기반 개발방법론, TDD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. TDD의 정의
        </div>
        <div class="para-cntnt">
            Test Case를 먼저 개발하고 Test Case를 통과하는 실제코드를 나중에 개발하는 개발방법론
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. TDD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. TDD의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/TDD.png" alt="TDD">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. TDD의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  Design for Testability - 소스코드의 의존성이 감소하고 독립적 테스트가 가능한 설계구조
  테스트 커버리지 확보 - 단위 테스트를 통한 테스트 커버리지 유지, 디버깅 시간 감소
  견고성 보장 - 발생 가능 오류에 대한 조기 탐지 가능
  Clean code that works - 작동하는 코드 지향
프로세스 요테구리체
  요구사항 / Userstory - 사용자, BA, 제품 개발자 등이 요구사항 Story 작성 / Need
  테스트케이스 작성 / Testcase - 동작 요구기능에 대한 인터페이스 개발 / ADD a Test(xUnit)
  코드구현 / Cleancode - 테스트에 대해 실행 가능한 코드를 빠르게 작성 / Make it Pass Triangulation
  리팩토링 / BadSmell - 중복코드/임시코드의 제고, 모듈화, 디자인 패턴 / Make it Right
  체크인 / Feedback - 모든 테스트가 작동하는 깔끔한 코드 저장 / Get feddback
TDD 사용패턴 빨초테디
  빨강막대 패턴 - 실패하는 작은 테스트를 작성
  초록막대 패턴 - 빨리 테스트가 작동해서 통과하도록함
  테스트 패턴 - 테스트-모듈 간 적합성, 성능 검증
  디자인 패턴 - 유사 도메인에서 발생하는 문제해결을 위한 BP모음
TDD와 BDD 비교
  목적 - 품질향상 &lt;&gt; 요구사항 이해
  테스트 - 단위 테스트 &lt;&gt; 통합 테스트
  작성방식 - 코드 기반 &lt;&gt; 스토리 기반

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
