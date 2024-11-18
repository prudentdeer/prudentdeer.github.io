---
title: AAA
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
      I. Authentification, Authorization, Accounting, AAA 
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. AAA의 정의
        </div>
        <div class="para-cntnt">
            불법적 서비스사용 방지위해 사용자인증, 권한검증, 과금기능 제공하는 프레임워크
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. AAA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. AAA의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/AAA.png" alt="AAA">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. AAA의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 
  Authentication
    PKI - 비대칭키 기반 인증 및 암호화
    PAP - ID, 비밀번호 평문전송, Password Authentication Protocol    
  Authorization
    ACL, CL, SL - 접속이 허가된 사용자에게 사용가능한 접근권한 정의
  Accounting 
    AMI - Account Management Information
    트래픽 - 사용자의 자원 사용에 대한 정보를 수집하여 과금, 감사, 보고서 기능
프로토콜 타라다이
  TACACS / TCP - 계층 패킷 전체 암호화
  RADIUS / UDP - 계층 패스워드 암호화
  Diameter / TCP, SCTP - 계층 패킷 전체 암호화
TACACS, RADIUS, Diameter 비교
  AAA - 분리 &lt;&gt; 통합 &lt;&gt; 분리
  프로토콜 - TCP &lt;&gt; UDP &lt;&gt; TCP, SCTP
  암호화 - 전체 &lt;&gt; 패스워드 &lt;&gt; 전체

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
