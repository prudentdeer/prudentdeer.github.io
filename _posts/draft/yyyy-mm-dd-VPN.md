---
title: VPN
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 보안]
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
      I. VPN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. VPN의 정의
        </div>
        <div class="para-cntnt">
            터널링기법을 사용해 두 네트워크 사이 통신을 전용회선 이용과 같은 효과를 내는 가상 네트워크 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. VPN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. VPN의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/VPN.png" alt="VPN">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. VPN의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          필요성 &nbsp; &nbsp;
  -&nbsp;본사, 지점, 지사 등 사업망 확대에 따른 전용망의 필요성 증가 &nbsp; &nbsp;
  -&nbsp;글로벌 기업의 해외 자회사간, 기업간 협업을 위한 전용망 범위 증가 &nbsp; &nbsp;
  -&nbsp;이동 근무 지원으로 기업 생산성 향상에 대한 기대 &nbsp; &nbsp;
  -&nbsp;전용망 구성과 관리를 위한 비용의 증가 및 사용량에 따른 대역폭의 탄력적 변경 필요  
구현기술 인터암키복 심
  인증 / 대칭키, 공개키 - 데이터를 보낸 자가 누구인지 인증 
  터널링 / 오버레이, 캡슐화 - 가상의 정보흐름 통로, 패킷을 사전에 암호화하는 방법을 규정한 IPSec이 업계표준 
  암호화 / DES, SEED - 기밀성 보장을 위한 메커니즘, 전송중인 정보의 공개방지 (DES, SEED 등 사용) 
  키관리 / IKE - 키의 안전한 관리 메커니즘, IKE (Internet Key Exchange) 프로토콜을 사용 
  복수 프로토콜 지원 / IPSec, SSL/TLS - 공용 네트워크에서 일반적으로 사용되는 프로토콜을 처리  
주요서비스 SIMM
  IPSec VPN - IP 프로토콜의 일부인 IPSec 프로토콜을 이용하여 VPN 구현 
    동작계층 : 3계층, 네트워크 계층 
    구성방법 : LAN to LAN VPN, 원격접속 VPN 
    적합한 환경 : 일반적인 본사 - 지사간 VPN 환경, C/S 기반 어플리케이션 운영 
    표준 : RFC 2401 
  SSL VPN - 보안통신 프로토콜을 통해 VPN 구현 
    동작계층 : 4~7계층, 전송 계층 ~ 응용 계층 
    구성방법 : 원격접속 VPN 
    적합한 환경 : 다수의 원격 사용자를 가진 환경, 웹 기반 어플리케이션 운영환경 
  MPLS VPN - 패킷 스위칭 기술인 MPLS 환경을 통해 VPN 구현 
    동작계층 : 데이터-링크 계층 
    구성방법 : LAN to LAN VPN, 원격접속 VPN 
    적합한 환경 : 시간에 민감한 어플리케이션 운영환경 (음성, 동영상) 
    표준 : RFC 2457 
  Mobile VPN (MVPN) : 보안에 취약한 모바일 네트워크 환경에서 신뢰성 있는 통신을 지원하기 위해 모바일 네트워크 구간에 VPN 암호화 기술 적용 
    적합한 환경 : 발전된 무선 기술을 통한 인터넷 접속으로 모바일 단말기에서 다양한 어플리케이션 사용 가능

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
