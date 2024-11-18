---
title: WAF
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
      I. 웹 애플리케이션 방화벽, WAF
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. WAF의 정의
        </div>
        <div class="para-cntnt">
            XSS, Injection 등 웹 취약점 탐지, 방어, 차단위해 웹서버 앞에 위치한 OSI 7계층 보안솔루션
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. WAF
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. WAF의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/WAF.png" alt="WAF">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. WAF의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          주요기능 공위부정 오유
  웹서버보호
    공격탐지/차단 - SQL Injection, XSS 등 탐지, 차단
    위변조방지 - 권한 접근제어, 실시간 차단, 모니터링
  컨텐츠보호
    부정로그인 방지 - 비정상적인 접근에 대한 접근제어
    정보유출방지 - DLP, DRM, 파일 업로드, 파일 검사
  메시지분석
    오류차단 - 에러정보를 차단, 정보 노출 방지
    URL 탐지 - Positive/Negative 정책, get/post 필터링
웹 방화벽 &lt;&gt; 방화벽 비교
  계층 - OSI Layer 7 &lt;&gt; OSI Layer 3~4
  포트 - 80, 특정 웹서버 포트 &lt;&gt; 모든 포트
  기반 - OWASP 취약점 기반 &lt;&gt; 룰셋 기반 (IP, 포트 제어)
- 알려지지 않은 공격은 웹방화벽, 방화벽으로 차단 불가
- 알려지지 않은 공격은 IDS, IPS, NGFW 적용 차단

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
