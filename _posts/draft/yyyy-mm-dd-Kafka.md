---
title: Kafka
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 데이터베이스]
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
      I. Pub/Sub 시스템, 카프카
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Kafka의 정의
        </div>
        <div class="para-cntnt">
            분산환경 실시간 데이터스트림 처리위해 Pub, Sub 모델기반 오픈소스 분산형 스트리밍 플랫폼
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Kafka
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Kafka의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Kafka.png" alt="Kafka">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Kafka의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  Pub, Sub 분리 - 수신, 송신 Pub/Sub 방식 적용
구성요소 (구성요소, 설명, 역할) 토프컨브주
  토픽 / 메시지 카테고리 - 메시지를 구분하기 위한 이름
  프로듀서 / 메시지 생성 - 메시지 생성, 메시지를 Broker에 전달
  컨슈머 / 메시지 사용 - Broker에게서 구독하는 메시지를 가져와 사용
  브로커 / 메시지를 관리 - 전달 받은 메시지를 topic별로 분류
  주키퍼 / 모니터링 – 메타데이터 관리 및 브로커의 정상상태 점검

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
