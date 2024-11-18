---
title: IPv6 전환
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
      I. IPv6 전환방법 듀터변
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IPv6 전환의 정의
        </div>
        <div class="para-cntnt">
              정의 - 하나의 시스템에서 IPv4 와 IPv6 프로토콜을 모두 처리하는 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IPv6 전환
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IPv6 전환의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IPv6-전환.png" alt="IPv6 전환">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IPv6 전환의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
              장점 - IPv4 혹은 IPv6 장비와 호환성 유지, DNS 주소 해석 라이브러리가 두 IP 주소 유형을 모두지원
    단점 - IP 계층의 프로토콜 스택 수정필요, 공인 IPv4 주소 사용으로 주소 고갈 문제 해결 불가능
    보안 - IPv4와 IPv6의 보안수준이 다른경우 / 인증기술, 접근제어, 침입탐지
  Tunneling (네트워크)
    정의 - IPv4 망에 터널을 만들어 IPv6 패킷을 통과시키는 기술
    종류 - Configuration Tunnel, Auto Tunnel, Tunnel Broker, 6 over 4, Teredo, DS-Lite, 6rd
    장점 - 가장 활발히 진행됐으며, 다양한 터널링 기술이 표준으로 제안됨
    단점 - 구현이 어려우며, 복잡한 동작과정, 터널 사용으로 인한 패킷 증가, 보안 위험성 증가 등
    보안 - 비인가된 터널링 생성으로 보안취약점 / 터널링 패킷 필터, 안티 바이러스
  Translation (게이트웨이)
    정의 - IPv4 망과 IPv6 망 사이에 주소변환기를 사용하여 상호 연동 시키는 기술
    종류 - 응용계층 게이트웨이 방식, 전송계층 릴레이 방식, 헤더변환 방식
    기술 - NAT-PT/SIIT, TRT, SOCKS 게이트웨이, BIS, BIA
    장점 - 각 네트워크상의 노드들이 듀얼스택을 탑재하지 않고 통신할 수 있음.
    단점 - 애플리케이션 별로 특성을 모두 반영해야 하므로 한계, 패킷을변환하는 과정에서 보안 취약
    보안 - 릴레이(경유) 오용으로 인한 보안 취약성 / 라우터 설정, 인증 필요

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
