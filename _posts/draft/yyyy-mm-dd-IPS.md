---
title: IPS
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
      I. 실내위치측위를 위한 IPS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IPS의 정의
        </div>
        <div class="para-cntnt">
            실내 위치를 파악하기 위해 WIFI, UWB, Beacon 이용, 측위기법 적용해 위치를 측정하는 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IPS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IPS의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IPS.png" alt="IPS">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IPS의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유현
  Wi-Fi 기반
    Cell ID - 가장 센 신호의 AP 접속 점 위치로 단말 위치 결정
    삼각측량 - 3개 이상 AP에서 RSSI 측정, 거리 환산
  비콘기반
    블루투스 - BLE 장치 간 거리로 측위 계산
  UWB 기반
    ToA - 전파 도달시간 계산, Time of Arrival
    TDoA - 도착신호의 시간차 계산. Time Difference of Arrival
    AoA - 도착 신호의 각도차이 분석, Angle of Arrival
활용방안
  재난, 안전, 교통 / 생활, 의료 / 쇼핑, 게임

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
