---
title: REST
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 디지털서비스]
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
      I. 무상태성 API, REST API
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. REST의 정의
        </div>
        <div class="para-cntnt">
            자원을 이름으로 구분하여고 행위, 자원, 표현 이용 자원의 상태정보를 주고받는 REST 기반 API
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. REST
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. REST의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/REST.png" alt="REST">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. REST의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징 유무캐자분계
  유니폼 인터페이스 - 한정적인 인터페이스로 수행하는 아키텍처 스타일
  무상태성 - 상태 정보를 저장하지 않는 단순한 구조
  캐시처리 - HTTP를 사용하므로 캐싱기능 적용가능 
  자체표현구조 - REST API 메시지만 보고도 쉽게 이해
  분리구조 - 클라이언트, 서버간의 구성요소 엄격히 분리
  계층형 구조 - 다중계층으로 구성, 보안, 로드 밸런싱, 암호화 계층
구성요소 행자표 
  행위 / HTTP - GET, POST, PUT, PATCH, DELETE의 Method를 제공
  자원 / URI - URI를 이용해 자원을 지정하고 상태에 대한 조작을 Server에 요청
  표현 / JSON, XML - Client와 Server가 데이터를 주고받는 형태로 JSON, XML, TEXT, RSS 등
HTTP 응답코드
  1xx - 전송 프로토콜 수준의 정보 교환
  2xx - 클라이언트 요청이 성고적으로 수행됨
  3xx - 클라이언트는 요청을 완료하기 위해 추가적인 행동을 취해야 함
  4xx - 클라이언트의 잘못된 요청
  5xx - 서버쪽 오류로 인한 상태코드
관련개념
  REST - 아키텍처 스타일
  REST API - REST 기반 서비스 구현 API
  RESTFul - REST 기본원칙을 성실히 지킨 서비스 디자인을 RESTFul 하다고 함

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
