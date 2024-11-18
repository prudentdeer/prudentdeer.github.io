---
title: SOA
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
      I. 서비스 기반 아키텍처, SOA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SOA의 정의
        </div>
        <div class="para-cntnt">
            기존 어플리케이션의 서비스를 조합함으로써, 새로운 어플리케이션을 구현할 수 있도록 한 아키텍처
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SOA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SOA의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SOA.png" alt="SOA">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SOA의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  프로세스 중심, 플랫폼 독립적, 어플리케이션 통합, 위치투명성, Loosely Coupled
핵심기술 데미호기등
  데이터교환 / XML - 인터넷 데이터 교환기술
  미들웨어 / ESB - 메시징을 통한 다수의 시스템에 Loosely Coupled한 방식으로 연결
  서비스호출 / SOAP - XML언어를 이용한 분산환경에서의 정보교환을 위한 프로토콜
  서비스기록 / WSDL - Web Service의 기능, 사용법 등을 기술한 XML기반의 언어
  서비스등록 / UDDI - 인터넷상에서 Web Service에 대한 정보 등록, 검색하는 공용 Registry 서비스
SOA 와 MSA 비교
  규모 - 대규모 &lt;&gt; 소규모
  통신 - ESB &lt;&gt; HTTP/REST
  데이터 - 통합 DB &lt;&gt; 개별 DB

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
