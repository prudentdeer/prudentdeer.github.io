---
title: Spring Framwork
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
      I. 전자정부 프레임워크의 핵심, 스프링프레임워크
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Spring Framwork의 정의
        </div>
        <div class="para-cntnt">
            개발 생산성향상과 고품질의 웹앱개발 위한 POJO, AOP, DI, 추상화 이용 오픈소스 프레임워크
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Spring Framwork
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Spring Framwork의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Spring-Framwork.png" alt="Spring Framwork">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Spring Framwork의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징 
  객체 관리 : 컨테이너에서 직접 객체관리 / 관리부담 감소
  제어반전 (IoC) : 컨트롤의 제어권이 프레임워크에 존재 / 스프링에서 사용자 코드 호출
  의존성 주입 (DI) : 서비스들간 의존성 존재할경우 연결 / XML 파일 이용 환경설정
  관점지향 (AOP) : 여러 모듈에서 공통사용하는 기능의 분리 / 추상화 트랜잭션 관리, 로깅, 보안 등
  영속성 : DB처리 라이브러리와 인터페이스 지원 / JDBC, iBatis 등
구성요소 WAS CDOM
  Web / Context, Multipart Request - Request 기반 프레임워크
  AOP / 핵심, 횡단관심사 - 횡단관심사의 분리로 코드 변경없이 더해지거나제거 가능
  Spring Core (IoC) / 의존성주입 : 객체간 의존성감소로 유연한대처, 재사용 가능성
  Context  / JUnit, DI : POJO 기반 접근, EJB 대체 및 통합
  DAO / JTA, Global 트랜잭션 : 대부분의 ORM 프레임워크와 통합 
  ORM / iBatis, Hibernate, Oracle : 객체관계형 모델 지원, 다양한 DB 인터페이스 제공
  MVC / JSP, Velocity : 이벤트 기반 프레임워크

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
