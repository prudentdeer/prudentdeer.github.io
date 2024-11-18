---
title: 클린 아키텍처
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
      I. Loosly Coupled, 클린 아키텍처
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 클린 아키텍처의 정의
        </div>
        <div class="para-cntnt">
            종속성 규칙, 추상화 개념으로 관심사를 분리시키고 의존도를 낮추는 4계층구조 아키텍처
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 클린 아키텍처
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 클린 아키텍처의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/클린-아키텍처.png" alt="클린 아키텍처">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 클린 아키텍처의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 엔유어인
  엔티티 계층 / 업무규칙, 도메인 - 핵심이 되는 비즈니스 규칙을 캡슐화
  유스케이스 계층 / 유즈케이스, 앱 규칙 - 어플리케이션 규모의 비즈니스 규칙을 포함
  IF 어댑터 계층 / 컨트롤러, 게이트웨이 - 데이터를 변환하는 어뎁터의 집합
  인프라 계층 / 프레임워크, DB - 웹 프레임워크와 같은 세부 정보를 나타내는 계층
주요원칙 DAS
  Dependency rule - 종속성의 흐름을 제어, 캡슐화를 통해 내부 계층을 외부 계층과 분리
  Abstraction principle - 가장 안쪽에 있는 계층이 제일 추상화된 영역
  SOLID - 확장가능하며 유지보수 가능한 유연한 소프트웨어 아키텍처를 만들기 위한 원칙

1. 안으로 갈 수록 변경 가능성이 낮아야 합니다.
2. 외부 영역은 내부 영역에 의존할 수 있지만, 내부 영역은 외부 영역에 의존할 수 없습니다.
3. 프레임워크에 의존하지 않습니다.
4. 유스케이스(UseCases)는 아키텍처에서 최우선이다.

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
