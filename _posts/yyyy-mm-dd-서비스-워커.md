---
title: 서비스 워커
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
      I. PWA 의 핵심 Building Block, 서비스 워커
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 서비스 워커의 정의
        </div>
        <div class="para-cntnt">
            웹 브라우저와 별개로 동작하며, 웹페이지 상호작용이 필요하지 않는 백그라운드 실행 스크립트
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 서비스 워커
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 서비스 워커의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/서비스-워커.png" alt="서비스 워커">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 서비스 워커의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 디싱프자프흐
  Process
    Decoupling - 등록 후 html 파일과 Decoupling 되어 독립적으로 구동
    Single Thread - 독립된 single thread로 작동
    Background - index.html에서 load되는 app.js르 통해 등록
  Language
    Promise - ES6 Promise를 광범위하게 사용하여 작성
    JavaScript - DOM에 직접 액세스 불가, 제어 대상 페이지와 통신 위해 postMessage 인터페이스 사용
  Network
    Proxy - 프로그램 가능한 네트워크 프록시, 페이지의 네트워크 요청 처리 방법을 제어
    HTTPS - 어떤 request든 intercept할 수 있기 때문에 secure deploy 환경 요구
서비스 워커 vs 웹 워커
  공통점 - DOM 연결불가능, 추가스레드에서 실행
  수명 - 브라우저와 독립적 &lt;&gt; 브라우저 탭 종속적
  네트워크 - 인터셉트 가능 &lt;&gt; 영향없음
  관계 - 모든 활성탭 제어 &lt;&gt; 페이지 당 여러개 가능

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
