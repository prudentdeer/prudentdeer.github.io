---
title: FaaS
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
      I. 서버리스 아키텍처의 대표적 기법 FaaS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. FaaS의 정의
        </div>
        <div class="para-cntnt">
            애플리케이션을 구성하는 여러 함수들을 클라우드에서 직접 실행하는 방식의 클라우드 서비스
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. FaaS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. FaaS의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/FaaS.png" alt="FaaS">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. FaaS의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          기술요소
  Event Driven - Event-Driven 아키텍처를 구현하는데 적합하며 사용자가 원하는 기능을 미리 작성해놓고 특정 이벤트에 의해 실행됨
  함수단위 호출 - 함수로 쪼개어 분산 컴퓨팅 자원을 준비, 호출, 조합하도록 함
  함수 개발비용 - 서버가 실행된 횟수와 시간(밀리세컨드. 1,000 분의 1 초)으로 산정
사례 
  함수 서비스 제공 : AWS의 Lambda, 마이크로소프트의 Azure Functions, 구글의 Google Cloud Functions

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
