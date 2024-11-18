---
title: ADN
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 네트워크]
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
      I. 네트워크 가속기술, ADN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ADN의 정의
        </div>
        <div class="para-cntnt">
            망 지연이 가장 큰 구간에 위치한 서버들간 트래픽을 빨리 전달 할 수 있도록 하는 가속기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. ADN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ADN의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/ADN.png" alt="ADN">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. ADN의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          핵심기술
  Route Optimization - 사용자와 Origin Server 사이의 라우팅 경로 최적화
  Packet Redundancy (FEC) - 동일 패킷을 서로 다른 경로를 통해 중복 전달
  Data Compression - 데이터 압축을 통해 전송량 최소화
  Data De-duplication - 동일 byte-stream에 대해서는 중복 전송을 하지 않아 전송량 최소화
  Application Optimization - 응용 레이어 프로토콜 최적화
  TCP Optimization - TCP 프로토콜 최적화

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
