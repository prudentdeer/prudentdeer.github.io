---
title: LDT
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
      I. 측위기술, LDT
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. LDT의 정의
        </div>
        <div class="para-cntnt">
            위치기반 서비스 제공을 위해 기지국, AP, 무선통신 이용 이동경로, 단말위치 측정 위치 측위기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. LDT
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. LDT의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/LDT.png" alt="LDT">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. LDT의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          측위기술 셀핑토아 알유직비
  WIFI 기반 
    Cell ID - 통신 기지국에 접속된 단말 위치를 해당 AP 위치로 매칭
    Finger printing - 실내 공간을 여러 셀로 분할, 각 셀의 RSSI 정보통한 측위
  기지국 기반
    ToA - 다수 AP 와 단말 사이 신호 전송 시간 측정
    TDoA - AP 들간 시각동기만으로 측위
    AoA - 단말에 수신되는 각도 측정 위치 계산
  무선통신 기반
    WPS - 무선 AP 의 SSID 와 MAC 주소 활용, 핑거프린팅 방식 
    RSSI - 센서로부터 전압레벨을 측정하여 실내위치 측위
    UWB - 고유 ID 를 32bit 로 송출, 광대역주파수 활용 측위
    Zigbee - 저전력성 Zigbee 탑재 단말이 AP 통해 단말위치 전송
    Bluetooth - BLE, Beacon 사용, 지오펜싱 기반의 전파맵 생성 측위

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
