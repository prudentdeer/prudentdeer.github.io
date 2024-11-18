---
title: 드라이브 바이 다운로드
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 보안]
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
      I. 드라이브 바이 다운로드
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 드라이브 바이 다운로드의 정의
        </div>
        <div class="para-cntnt">
            웹페이지에 악성코드를 설치하고 사용자가 접속하는 순간 동의없이 실행되는 사회공학적 공격기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 드라이브 바이 다운로드
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 드라이브 바이 다운로드의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/드라이브-바이-다운로드.png" alt="드라이브 바이 다운로드">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 드라이브 바이 다운로드의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          대응방안
  서버 측면 
    SQL Injection, XSS 공격 등 웹페이지에 코드 삽입을 사전 또는 사후에 탐지 
    Secure Coding 적용 
    샌드박스 활용 악성코드 사전탐지 
    지속적인 보안상황 모니터링을 통한 보안정책 업데이트 
    API 취약점 솔루션 도입 통합 API 취약점 제거 
  클라이언트 측면 
    Client Honey Pot 이용, 악성 웹사이트로 의심되는 웹사이트 분석 (악성 웹사이트 조기 탐지)
    1) Low-interaction Client Honey Pot : 의심 페이지를 다운로드 하여 정적 분석 
    2) High-interaction Client Honey Pot : 의심 웹페이지를 직접 방문하여 발생하는 시스템 변화를 모니터링 
    SW 최신유지 
    웹필터링 SW설치 
    파이어폭스 브라우저 NoScript 설치 
    자바 비활성화 
    블레이드(Blade) – 새로운 윈도우 면역시스템 
    관리자 권한 접속 금지 
    형상관리 활용 측면 - 매일 정적 및 동적 페이지 검사 수행 

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
