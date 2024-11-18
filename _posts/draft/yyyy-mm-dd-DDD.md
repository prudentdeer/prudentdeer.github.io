---
title: DDD
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
      I. 도메인 중심설계, DDD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DDD의 정의
        </div>
        <div class="para-cntnt">
            도메인 이해를 바탕으로한 도메인 모델, 유비쿼터스 언어, 엔티티 기반 설계하는 설계기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DDD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DDD의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DDD.png" alt="DDD">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DDD의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          전술적 설계 - 도메인 모델을 만드는 데 사용할 수 있는 디자인 패턴 집합을 제공
  계층구조 유앱도인 엔벨어도레
    User Interface - 사용자 요청을 하위 계층에 전달
    Application - App 상태 관리, Biz처리는 도메인에 요청
    Domain - Domain 정보 및 상태 포함 Biz. Logic 제공
    Infrastructure - 다른 계층 지원 라이브러리 영속성 구현
  구성요소 
    Entity - 고유식별자를 가지는 객체, 자신의 생명주기를 가짐, 도메인의 고유한 개념을 표현
    Value - 고유식별자를 가지지 않음, 하나의 값을  표현할때 사용, 다른 밸류 타입의 속성으로도 사용
    Aggregate - 연관된 엔티티와 밸류 객체를 개념적으로 하나로 묶은 것
    Domain Service - 도메인 모델의 영속성으로 처리
    Repository - 도메인 모델의 영속성을 처리, DB 전담으로 처리
전략적 설계 - 비즈니스 상 전략적으로 중요한 것을 구분하고 찾는 과정
  절차 유도서바 컨도 코서제
    유비쿼터스 언어 - 모델링에 참여하는 사람들이 사용하는 공통된 언어 정의
    도메인 식별 - 해결해야 할 문제 영역 
    서브도메인 식별 - 도메인 내 문제 해결 위해 여러 서브 도메인으로 나눔
    바운디드 컨텍스트 식별 - 도메인 모델이 존재하는 명시적인 경계
    컨텍스트 맵 작성 - 두 개 이상의 바운디드 컨텍스트 사이의 연관성을 보여주는 다이어그램
    도메인 모델 - 실제 세계를 반영하여 실제 세상을 더 잘 이해할 수 있도록 추상화 되고 구체적인 설계
  구현모델
    Core Sub-Domain: 비즈니스 목적 달성을 위한 핵심 도메인으로 차별화를 위해 가장 많은 투자가 필요함
    Supporting Sub-Domain: 핵심 도메인을 지원하는 도메인
    Generic Subdomains:  공통 기능(메일, SSO 등) 도메인으로서 3rd Party제품을 구매하는것이 효율적임

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
