---
title: 중앙처리장치 구성
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 컴퓨터구조]
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
      I. [정의] 컴퓨터의 가장 중요한 부분으로서 명령을 해독하고 산술논리연산이나 데이터 처리를 실행하는 장치
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 중앙처리장치 구성의 정의
        </div>
        <div class="para-cntnt">
                             Register Set - PC, IR, AC, MAR, MBR, SP
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 중앙처리장치 구성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 중앙처리장치 구성의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/중앙처리장치-구성.png" alt="중앙처리장치 구성">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 중앙처리장치 구성의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
                             Control Unit - 제어장치, 명령해석,실행, 흐름통제, CISC, RISC
                   internal CPU Bus - 내부 CPU버스, 직렬,병렬
[동작원리] 
명령어 인출&gt;명령어 해석&gt;데이터 인출&gt;데이터 처리&gt;데이터 쓰기
(IF (pc,ir) &gt;ID &gt; DF (mar,mbr) &gt; DP (ac,mbr) &gt;DS (mar,mbr,str) )

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
