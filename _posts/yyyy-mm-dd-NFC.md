---
title: NFC
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
      I. 비접촉거래 기반기술, NFC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NFC의 정의
        </div>
        <div class="para-cntnt">
            13.56Mhz 주파수 이용, 424Kbps 전송속도, 10cm내외 근거리 양방향 무선통신 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. NFC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NFC의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/NFC.png" alt="NFC">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. NFC의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          표준
  ISO 18092, ISO 14443
구성요소 안유엔 피카리
  통신요소
    안테나 - NFC 통신을 위한 주파수 전송
    USIM - 결제 정보 등 사용자의 정보를 저장
    NFC 칩셋 - 데이터를 송수신 하고 처리
  동작방식
    P2P - NFC 기기간 데이터 교환
    카드 애뮬레이션 - 결제 및 티케팅 수행
    리더, 라이터 - 카드, RFID, 태그, 키오스크 등
취약점 - RF 신호 도청
보안 - 토큰 사용
NFC와 MST 비교
  기반 - 전자기 유도 &lt;&gt; 자기장 발생
  통신모드 - 양방향 &lt;&gt; 단방향 
  서비스 - 애플, 삼성페이 &lt;&gt; 삼성페이
  수수료 - 발생 &lt;&gt; 없음
- NFC 보안 취약성(마그네틱카드기반)으로 NFC로 전환진행
- 둘다 자기장 이용

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
