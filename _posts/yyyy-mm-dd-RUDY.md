---
title: RUDY
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
      I. RUDY = Slowroris (RU-Dead-Yet?) 
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. RUDY의 정의
        </div>
        <div class="para-cntnt">
            웹서버와 커넥션을 맺고 비정상 HTTP 헤더를 전송해 커넥션자원을 고갈시키는 DDoS 공격기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. RUDY
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. RUDY의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/RUDY.png" alt="RUDY">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. RUDY의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          절차
  HTTP에선 헤더의 끝을 /r/n/r/n 이라는 개행문자로 구분한다.
  공격자는 이 마지막 개행문자를 보내지 않고 지속적으로 의미없는 변수를 추가한다.
  서버는 헤더 정보가 아직 전송 중이라고 인식하고 연결을 유지한다.
대응
  http timeout - 일정 시간 내로 유입이 안되면 종료
  웹방화벽

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
