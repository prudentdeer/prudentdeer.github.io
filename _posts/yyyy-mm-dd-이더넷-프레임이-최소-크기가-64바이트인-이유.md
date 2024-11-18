---
title: 이더넷 프레임이 최소 크기가 64바이트인 이유
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
      I. - 10Base5 사용하는 경우, Half duplex 방식, CSMA/CD 방식의 충돌문제
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 이더넷 프레임이 최소 크기가 64바이트인 이유의 정의
        </div>
        <div class="para-cntnt">
          이유
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 이더넷 프레임이 최소 크기가 64바이트인 이유
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 이더넷 프레임이 최소 크기가 64바이트인 이유의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/이더넷-프레임이-최소-크기가-64바이트인-이유.png" alt="이더넷 프레임이 최소 크기가 64바이트인 이유">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 이더넷 프레임이 최소 크기가 64바이트인 이유의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            전송시간 계산
    10Base5의 동축케이블은 500m당 2.8usec, 2500m = 14usec
    500m 신호 송신 + 수신 = 14usec * 2 = 28usec (되돌아와야 하므로 *2)
  지연시간 계산
    리피터 1대당 지연시간 3usec
    리피터 4대의 지연시간 = (3usec * 4) * 2 = 24usec (되돌아와야하므로 *2)
  전송 + 지연시간 계산
    2500m 를 송수신하는데 걸리는 시간 = 28usec + 24usec = 52usec
    바이트를 맞추기 위해 51.2usec 으로 진행
  최소길이 계산 (충돌이 발생하는지 안하는지 감지할 동안 프레임이 계속 전송되고 있어야 하기때문에)
    전체 왕복시간이 51.2usec 가 되려면, (10Base5는 1bit 전송하기위해 0.1usec 필요)
    51.2usec가 걸리려면 ?
    512bit가 필요함
    이걸 바이트로 환산하면 512 / 8 = 64byte

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
