---
title: 접근제어의 비교
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
      I. 접근통제 모델의 비교
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 접근제어의 비교의 정의
        </div>
        <div class="para-cntnt">
          보안요소 - 기밀성 &lt;&gt; 무결성 &lt;&gt; 무결성
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 접근제어의 비교
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 접근제어의 비교의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/접근제어의-비교.png" alt="접근제어의 비교">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 접근제어의 비교의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          접근통제 - DAC &lt;&gt; MAC &lt;&gt; MAC
기반 - 상태 컴퓨터 모델, 다중계층 보안, 정보흐름 모델 &lt;&gt; 상태 컴퓨터 모델, 다중계층 보안, 정보흐름 모델 &lt;&gt; 직무분리, 감사
속성 - No Read up, No Write down &lt;&gt; No Read Down, No Write up &lt;&gt; 프로그램을 통한 주체와 객체의 접근통제

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
