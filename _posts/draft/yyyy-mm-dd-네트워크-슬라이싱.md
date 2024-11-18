---
title: 네트워크 슬라이싱
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
      I. 5G의 핵심기술, 네트워크 슬라이싱
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 네트워크 슬라이싱의 정의
        </div>
        <div class="para-cntnt">
            물리적으로 하나의 네트워크를 논리적 분리해 서비스 특화된 전용 네트워크를 제공하는 기술 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 네트워크 슬라이싱
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 네트워크 슬라이싱의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/네트워크-슬라이싱.png" alt="네트워크 슬라이싱">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 네트워크 슬라이싱의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          핵심기술 ACID NCNM
  SDN
    Application - NW OS 상위에서 사용자 서비스 지원 
    Control Plane - 글로벌 관점에서 전체 망 제어 
    Interface - Data Plane과 Control Plane간 연계
    Data Plane - 단순 패킷 포워딩, 스위칭 기능 구현 
  NFV (Network Function Virtualization)
    NFVI - 물리적 HW 자원의 가상화 실행환경 제공, Network Function Virtualization Infrastructure 
    CSMF - 서비스 요구를 네트워크 슬라이싱과 요구로 변환, Communication Service Management Function
    NSSF - 네트워크 슬라이스 관리 및 선택기능, Network Slice Selection Function
    MANO - 물리적/SW적 자원관리 오케스트레이션, Management And Orchestration

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
