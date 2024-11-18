---
title: VxLAN
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
      I. VLAN의 확장, VxLAN의 개요
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. VxLAN의 정의
        </div>
        <div class="para-cntnt">
            가상환경 대규모 네트워킹 위해 레이어2 확장, UDP 터널링 이용 네트워크 가상화 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. VxLAN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. VxLAN의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/VxLAN.png" alt="VxLAN">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. VxLAN의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  제한된 확장성 극복, SDN 기반기술
기술요소
  핵심기술 븨엔븨
    VTEP - 터널간 캡슐화, 디캡슐화를 수행 / VXLAN Tunnel End Point
    NVE - 캡슐화, 디캡슐화가 발생하는 인터페이스 / Network Virtualization Interface
    VNI - VLAN과 VXLAN segment 간 식별자 번호 / Virtual Network Identifier
  기반기술 개세오언
    Gateway - VXLAN간 또는 VXLAN 과 Non-VXLAN간의 통신을 위한 Gateway
    Segment - VM간 통신을 위한 VXLAN Layer 2 overlay network 
    Overlay Network - 물리 네트워크 위에 성립되는 가상의 컴퓨터 네트워크
    Underlay Network - 실제 물리적 장비들을 이용한 네트워크 인프라
VxLAN과 VLAN 비교
  주소공간 - 24비트 &lt;&gt; 12비트
  작동레이어 - L2, L3 &lt;&gt; L2
  서브넷 - 가능 &lt;&gt; 불가능
- MAC주소 한계극복과 유연한 구성이 가능
VxLAN의 사용이유
  MAC주소 한계 - 기존 VLAN 대비 대량의 MAC 주소 생성
  유연한 구성 - 구성 IP가 바뀔시 서브 IP 와 게이트웨이를 변경할 필요가 없음

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
