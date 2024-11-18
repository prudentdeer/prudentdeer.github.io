---
title: IoC
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
      I. 제어의 역전, IoC 
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IoC의 정의
        </div>
        <div class="para-cntnt">
            메서드나 객체의 호출이 개발자가 아닌 외부에서 결정되는 것을 의미하는 디자인 패턴
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IoC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IoC의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IoC.png" alt="IoC">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IoC의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  객체지향 설계, 재사용성 향상, 의존성 관리 용이
유형
  DL / Dependency Lookup - 의존성 검색. 저장소에 저장되어 있는 빈(Bean)에 접근하기 위해 Lookup
  DI / Dependency Injection - 객체 간 의존성을 개발자가 객체 내부에서 직접 호출(new)하는 대신, 외부에서 객체를 생성해서 넣어주는 방식 

Spring 에서는 xml파일 또는 어노테이션 방식으로 스프링 컨테이너에 Bean(객체)를 등록하기만 하면,
스프링 컨테이너에서 Bean의 생명주기(생성 -&gt; 의존성 설정 -&gt; 초기화 -&gt; 소멸)를 전부 관리해준다.

즉, 객체에 대한 제어권이 컨테이너로 역전되기 때문에 제어의 역전이라고 하는 것이다.

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
