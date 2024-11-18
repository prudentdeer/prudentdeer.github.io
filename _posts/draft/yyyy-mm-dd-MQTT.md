---
title: MQTT
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
      I. 제한된 환경 메시지 프로토콜, MQTT
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MQTT의 정의
        </div>
        <div class="para-cntnt">
            IoT 환경에서 QoS 제공위해 Pub/Sub, Broker 이용하는 저전력, 고효율 네트워크 프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MQTT
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MQTT의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MQTT.png" alt="MQTT">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MQTT의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 펍섭브토 012
  핵심구성
    Publisher - 데이터 발행, Push 제공
    Subscriber - 토픽 구독요청, Pull 제공
    Broker - Pub, Sub 중계 API 역할
    Topic - 계층구조 메시지 전송
  QoS
    QoS 0 - 한번만 전송
    QoS 1 - 적어도 한번 전송
    QoS 2 - 정확히 한번 전송
MQTT와 MQTT-SN의 비교 (센서네트워크)
  프로토콜 : TCP/IP 기반 &lt;&gt; UDP, ZigBee, LoRa
  브로커 : 바로 연결 &lt;&gt; 브로커에 등록 후 연결
  토픽 : 계층 구조 &lt;&gt; 토픽 이름
  메시지 : 32비트 &lt;&gt; 16비트
&gt;&gt; MQTT-SN은 토픽 aliasing, 커넥티드 슬립기능 지원

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
