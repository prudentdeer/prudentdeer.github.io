---
title: NFV
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
      I. 네트워크 기능 가상화 NFV의 개요
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NFV의 정의
        </div>
        <div class="para-cntnt">
            하드웨어로 구현된 네트워크 기능들을 소프트웨어 형태의 가상장비로 운용하는 가상화 기술 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. NFV
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NFV의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/NFV.png" alt="NFV">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. NFV의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          목적 &nbsp; &nbsp;
  서비스 유연성 향상, 가상화로 표준화된 대용량 장비 개발  
구성요소 
  네트워크 기능
    VNFs – 소프트웨어로 구현한 네트워크 기능 (Virtualized Network Functions)
    VNFM - VNF 기능, 장애관리, 설정, 보안 등 (VNF Management)
  인프라 자원
    NFVI – 인프라 H/W 및 가상화 자원 (NFV Infrastructure)
    VIM - 인프라 및 가상화 자원 관리 서비스 (Virtualized Infrastructure Management)
  NFV 환경관리
    NFVO – NFV 환경의 네트워크 오케스트레이션 (NFV Orchestration)
NFV와 SDN 비교
  실제구현 - 소프트웨어 기능을 VM에 탑재 &lt;&gt; 중앙집중 제어와 네트워크 프로그램화
  운영주체 - 통신 서비스 사업자 &lt;&gt; 데이터센터, 클라우드 사업자
  핵심목표 - Data Plane의 가상화 &lt;&gt; Control Plane의 소프트웨어화
  표준화 기구 - ETSI NFV Workgroup &lt;&gt; ONF(Open Networking Forum)

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
