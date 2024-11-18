---
title: FIDO
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
      I. 생체 인식 기반 차세대 인증 기술, FIDO
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. FIDO의 정의
        </div>
        <div class="para-cntnt">
            온라인 환경에서 지문, 홍채, 안면 인식 등 생체 인식 기술 기반 UAF, U2F 인증하는 차세대 인증기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. FIDO
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. FIDO의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/FIDO.png" alt="FIDO">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. FIDO의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  생체 인증 - 계정을 직접 입력하는 대신 교유한 생체인증정보 인증 / 홍채, 지문, 정맥
  신속성, 편의성 - 다양한 인증수단을 통한 빠른 인증 / UAF 프로토콜
  비밀번호 보완 - 입력한 비밀번호에 대해 2차 인증 / U2F 프로토콜
구성요소
  FIDO 클라이언트 - FIDO 인증 토큰과 인증 API 연동, 등록, 인증, 조회 서비스
  FIDO 서버 - 클라이언트와 UAF 프로토콜 송수신, 인증 내용 검증 역할
  FIDO 프로토콜 - 사용자 디바이스와 서버 간에 세가지 메시지를 전달
UAF, U2F
  UAF 프로토콜 - 지문, 음성 등 생체 정보기반 디바이스 인증 (Universal Authentication Framework)
    – 지문, 음성 등 생체 정보기반 인증
    – 생체 정보는 디바이스에서 인증용 저장
    – FIDO 서버에 생체 정보 전송/저장 안함
  U2F 프로토콜 - 1차 인증(생체) 후 2차(보안 매체) 인증 (Universal 2nd Factor)
    - 1차 인증(생체) 후 2차(보안 매체) 인증
    – USB, BLE, NFC, LTE 등 다양한 인증방식
FIDO 1.0 과 FIDO 2.0 의 비교
  RP 클라이언트 - 모바일 앱 &lt;&gt; 웹브라우저 확장
  FIDO 클라이언트 - 단말제조사 제공 &lt;&gt; 플랫폼 제공
  ASM - 인증제조사, 단말제조사 &lt;&gt; 플랫폼 제공
  인증자 - 단말 제조사 제공 &lt;&gt; 빌트인 혹은 외부 인증자
  주요 프로토콜 - UAF 프로토콜 &lt;&gt; U2F 프로토콜

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
