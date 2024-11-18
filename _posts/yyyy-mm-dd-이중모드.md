---
title: 이중모드
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 운영체제]
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
      I. 시스템의 오동작 방지, OS 이중모드
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 이중모드의 정의
        </div>
        <div class="para-cntnt">
            운영체제를 보호하기 위해, 커널 모드와 사용자 모드를 구분해 시스템 자원접근 제한하는 모드
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 이중모드
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 이중모드의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/이중모드.png" alt="이중모드">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 이중모드의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 커유 특일 공일
  모드
    커널모드 - OS가 사용하며 특권명령 가능
    유저모드 - 응용프로그램사용, 일반명령 가능
  명령
    특권명령 - 관리자 모드에서만 내릴 수 있는 명령 / STOP (cpu의 동작 멈춤), RESET (초기화)
    일반명령 - 일반 사용자들도 이용할 수 있는 명령
  Mode flag
    Mode 0 - 커널 모드, 관리자 권한 
    Mode 1 - 사용자 모드, 일반 사용자
커널모드와 유저모드의 비교
  제어권 - 운영체제 &lt;&gt; 사용자
  Mode bit - 0 &lt;&gt; 1
  명령 - 특권 명령 &lt;&gt; 일반명령
  예시 - stop, kill &lt;&gt; print

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
