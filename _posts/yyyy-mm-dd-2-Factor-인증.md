---
title: 2 Factor 인증
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
      I. 다중인증 보안강화, 2 Factor 인증
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 2 Factor 인증의 정의
        </div>
        <div class="para-cntnt">
            기존의 지식기반 ID/Password 인증에 소유기반 인증 및 생체인증 요소를 추가한 인증 방법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 2 Factor 인증
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 2 Factor 인증의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/2-Factor-인증.png" alt="2 Factor 인증">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 2 Factor 인증의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          절차
  1차 인증요소 제공 - 사용자 정보인 지식기반 방식으로 사용자 인증을 시도 
  2차 인증요소 제공 - 소유기반 인증(OTP, 인증서), 생체기반 인증(지문, 홍채) 
  인증확인 - 1차 인증과 2차인증 정보를 확인하고 두가지가 모두 확인되었을 때 인증 완료
인증요소
  1차 인증
    지식기반 인증 - 패스워드, pin번호
  2차 인증 
    소지기반 인증 - 공인인증서, OTP, 문자인증, 토큰, 스마트카드
    생체기반 인증 - 지문, 얼글, 홍체, 정맥

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
