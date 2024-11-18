---
title: SOAP
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
      I. XML 웹서비스용 통신프로토콜, SOAP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SOAP의 정의
        </div>
        <div class="para-cntnt">
            HTTP, HTTPS, SMTP 등을 통해 XML 기반의 메시지를 네트워크 상에서 교환하는 프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SOAP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SOAP의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SOAP.png" alt="SOAP">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SOAP의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 인해바컨
  SOAP Envelope - Root tag로써 SOAP 메시지 시작을 나타냄
  SOAP Header - 가외 정보를 나타내기 위한 것으로 생략가능
  SOAP Body - 주 내용이 들어가는 태그, 다양한 형태의 태그들
  SOAP Content - 서비스에 대한 요청이나 응답
SOAP vs REST
  정의 - XML 기반 &lt;&gt; HTTP 기반
  공통점 - SOA 통신, HTTP 사용
  포맷 - XML, JSON &lt;&gt; 주로 JSON
  보안 - 표준화 기술 제공 &lt;&gt; 취약함

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
