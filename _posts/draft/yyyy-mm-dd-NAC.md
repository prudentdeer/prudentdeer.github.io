---
title: NAC
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
      I. IEEE 802.1x, NAC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NAC의 정의
        </div>
        <div class="para-cntnt">
            Endpoint 접근 전 보안정책 준수여부를 검사하여 접속을 인증 및 차단하는 접근제어 시스템
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. NAC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NAC의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/NAC.png" alt="NAC">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. NAC의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            관련표준 - IEEE 802.1x
동작절차
  네트워크 접근요청 - PC 사용자는 최초 네트워크에 대한 접근을 시도
  사용자, PC인증 - NAC에 등록된 MAC 주소를 통해 사용자PC 인증하거나 SSO와 연계하여 네트워크에 접근 적절성 여부 검토 (802.1x, RADIUS, AD, MAC)
  네트워크 접근허용 - 인증이 완료되면 네트워크에 대한 접근허용
  네트워크 접근차단 - 보안정책 인증 실패 시 네트워크 접근 차단 및 격리
NAC, Firewall 비교
  목적 - 단말 접근제어 &lt;&gt; 통신 접근제어
  운영 - 정적 정책, 단말중심 &lt;&gt; 동적 정책, 네트워크 중심
  접근제어 - 내부 접근제어 &lt;&gt; 내부, 외부간 접근제어

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
