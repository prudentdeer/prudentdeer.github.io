---
title: SDN
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
      I. 소프트웨어로 네트워크 관리 시작, SDN의 개요
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SDN의 정의
        </div>
        <div class="para-cntnt">
            네트워크 장비의 SW와 HW영역을 분리하여 OpenFlow 통해 SW 기반 네트워크 제어기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SDN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SDN의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SDN.png" alt="SDN">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SDN의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 ACID OCA
  Application / Application - Network OS 상위에서 사용자 서비스를 지원하는 프로그램 
  Control Plane / Control - 기존 네트워크 제어기능 중앙집중화 구현
  Interface / OpenFlow - Data Plane과 Control Plane간 연계
  Data Plane / Forward Engine - Openflow 지원스위치, 기존 스위치에 Openflow 기능 추가
주요기술 
  API 플랫폼 - 네트워크와 애플리케이션을 연계 
  Controller 및 Agent - 다양한 네트워크 장비와 애플리케이션 사이에서 역할 
  Overlay - 물리적인 네트워크와 가상 네트워크를 포괄하는 네트워크 가상화 플랫폼

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
