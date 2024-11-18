---
title: JSON
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
      I. 경량의 데이터 교환형식, JSON
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. JSON의 정의
        </div>
        <div class="para-cntnt">
            데이터 송수신시 표현하는 방법으로 데이터를 객체화하는 javascript기반 경량 데이터 교환형식
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. JSON
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. JSON의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/JSON.png" alt="JSON">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. JSON의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  이해용이, 다양한 언어지원, 경량 데이터 교환 포맷, JavaScript 구문 형식 준수, 프로그램언어/플랫폼 독립적
문법과 변환방법
  문법 - { "product" : "pencil", "price" : 1000 }
  변환방법
    JSON.parse() - 인자로 전달된 문사열을 자바스크립트의 데이터로 변환
    JSON.stringify() - 인자로 전달된 자바스크립트의 데이터를 문자열로 변환
JSON vs XML
  메타데이터 비중 - 낮음 &lt;&gt; 높음
  파싱 편의성 - 높음 &lt;&gt; 낮음
  파싱 성능 - 높음 &lt;&gt; 낮음
  안전성 - 낮음 &lt;&gt; 높음
  인코딩 - UTF-8 &lt;&gt; 다양함

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
