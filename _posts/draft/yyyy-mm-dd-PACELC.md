---
title: PACELC
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
      I. CAP 이론의 보완, PACELC 이론
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. PACELC의 정의
        </div>
        <div class="para-cntnt">
            CAP 이론의 단점을 보완하기 위해 네트워크 장애 상황과 정상 상황으로 나누어서 설명하는 이론
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. PACELC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. PACELC의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/PACELC.png" alt="PACELC">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. PACELC의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          PACELC 이론설명
  장애 / 정상 / 설명
  P+A / E+L - 장애상황에서 가용 노드만 반영, 정상상황에서 Latency 우선 고려
  P+A / E+C - 장애상황에서 가용 노드만 반영, 정상황에서 모든 메시지 보장
  P+C / E+L - 장애상황에서 Timeline 일관성 보장, 정상상황에서&nbsp; Latency 우선 고려
  P+C / E+C - 장애상황에서 일관성 우선 보장, 정상상황에서 모든 노드 동일 메시지 보장
PACELC 이론 따른 NoSQL 분류 몽볼카피
  PA / EC - Mongo DB  
  PC / EC - Volt DB
  PA / EL - Cassandra
  PC / EL - PNUTS

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
