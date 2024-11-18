---
title: 제로 트러스트경계보안비교
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
      I. 경계보안 모델 선접속 후인증
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 제로 트러스트경계보안비교의 정의
        </div>
        <div class="para-cntnt">
            방화벽을 놓고 경계 내부 사용자 신뢰, 외부에 있으면 신뢰할 수 없는 것 가정하는 보안모델
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 제로 트러스트경계보안비교
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 제로 트러스트경계보안비교의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/제로-트러스트경계보안비교.png" alt="제로 트러스트경계보안비교">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 제로 트러스트경계보안비교의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          제로 트러스트 모델과 경계보안 모델
  핵심 - 무신뢰 기반 매번 인증 &lt;&gt; 한 번 인증된 사용자 신뢰
  원리 - 지속적 인증 &lt;&gt; 일회성 인증
  보안성 - 각 자원에 접근 권한 부여 &lt;&gt; 내부 접속 후에는 제어 어려움
  주요기술 - IAM, XDR, SIEM &lt;&gt; 방화벽, VPN, NAC
  장점 - 다양화, 지능화 대응 &lt;&gt; 효율적, 관리 편의
  단점 - 고비용, 비효율 &lt;&gt; 계정탈취 보안 마비

적용분야 비교
  클라우드 - 자원별 인증 &lt;&gt; ID, PW 기반 인증
  IoT - 기기별 인증 &lt;&gt; 관리 앱, 공유기 기반
  MSA - 서비스별 인증 &lt;&gt; SSO 기반
  API - Endpoint 별 인증 &lt;&gt; 로그인, 쿠키, 헤더 
  BYOD - 반입, 사용시마다 &lt;&gt; 반입시
  망분리 - SDP 경계 &lt;&gt; 물리적 망 분리

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
