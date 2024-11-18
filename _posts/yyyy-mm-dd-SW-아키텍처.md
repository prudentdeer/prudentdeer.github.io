---
title: SW 아키텍처
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
      I. 컴포넌트와 인터페이스 간의 구조, 소프트웨어 아키텍처
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SW 아키텍처의 정의
        </div>
        <div class="para-cntnt">
            소프트웨어 외부적으로 보여지는 특성, 컴포넌트들과 그들의 상호관계로 구성되는 시스템구조
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SW 아키텍처
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SW 아키텍처의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SW-아키텍처.png" alt="SW 아키텍처">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SW 아키텍처의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          설계원리 분단추모정
  분할과 정복 - 세분화된 작은 시스템부터 개발 (상향식)
  단계적 분해 - 기능 세분화 후 점진적 구체화 (하향식)
  추상화 - 과정 추상화, 데이터 추상화, 제어 추상화
  모듈화 - 작업 단위화, 응집도 및 결합도
  정보은닉 - 모듈간 독립화, 인터페이스 통해 필요정보만 송수신
수립절차 요분설평
  요구사항 분석 / 요구식별, 요구명세 - 요구사항을 정의하고 수집, 기능 비기능적 요구사항 분석
  아키텍처 분석 / 품질속성식별, 우선순위 - 품질속성 식별, 품질속성 우선순위 결정
  아키텍처 설계 / 관점, 스타일선택 - 관점 및 뷰 정의, 아키텍처 스타일 정의
  평가 및 승인 / 평가, 승인 - 아키텍처 평가, 아키텍처 승인
고려사항, 아키텍처 드라이버 기제품
  기능요구사항 - 시스템이 구현해야 하는 기능 요구사항에 대해 설계 단계에서 책임 할당
  제약사항 - 프로그래밍 언어, Legacy 재사용, H/W, COTS
  품질속성 - 시스템 품질속성, 비즈니스 품질속성, 아키텍처 품질속성

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
