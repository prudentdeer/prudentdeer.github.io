---
title: SASE
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
      I. 클라우드 통합 보안 아키텍처, SASE
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SASE의 정의
        </div>
        <div class="para-cntnt">
            SD-WAN 서비스에 CASB, ZTNA, FWaaS, SWG 클라우드 보안기능 통합 보안 아키텍처
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SASE
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SASE의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SASE.png" alt="SASE">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SASE의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          기술요소 SSP CZFS
  네트워크 가상화
    SD-WAN - 인터넷망 기반 Overlay Network 구현
    SDP - 신원을 기반으로 리소스에 대한 액세스 제어 프레임워크 (Software Defined Perimeter)
    POP - 원격 사용자와 클라우드 보안 연동 접점 (Point of Presence)
  클라우드 보안
    CASB - 클라우드 사용자 모니터링 (Cloud Access Security Broker)
    ZTNA - 기본 비신뢰 기반 보안정책 (Zero Trust Network Access)
    FWaaS / NGFW - URL 필터링, APT, IPS, DNS 보안 기능 제공 (FireWall as a Service / Next Generation FireWall)
    SWG - 웹, 인터넷 트래픽 기준 악성코드 탐지, 접속 차단 수행 (Secure Web Gateway)
SASE 와 VPN 비교
  구현방식 - 클라우드 기반의 Muti-Edge 지원 &lt;&gt; Site to Site, Remote Access VPN
  핵심기술 - SWG, CASB, ZTNA, SD-WAN &lt;&gt; IPsec, SSL/TLS
  유동성 - Any Device, Any Where &lt;&gt; Site 간 고정 연결, 한정된 Device

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
