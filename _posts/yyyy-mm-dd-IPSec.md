---
title: IPSec
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
      I. 안전통신위한 보안기술, IPSec
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IPSec의 정의
        </div>
        <div class="para-cntnt">
            NW 계층의 안전통신을 위해 AH, ESP 이용 인증, 무결성, 기밀성 보장 IP 보안 프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IPSec
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IPSec의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IPSec.png" alt="IPSec">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IPSec의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          필요성
  IP 보안 취약성, 비용 절감
구성요소 연정연정 아에이삭
  정책
    SA - 보안 연관
    SP - 보안 정책
    SAD - 보안 연관 데이터베이스
    SPD - 보안 정책 데이터베이스
    PAD - 피어 인가 데이터베이스, 인증된 피어 또는 피어 그룹 식별 목적
  프로토콜
    AH - 데이터 인증, 무결성, anti-replay 서비스 제공, Authentication Header
    ESP - 캡슐화 통한 기밀성 보장, Encapsulating Security Payload
    IKE - 사용할 암호 키와 알고리즘을 협상 (Internet Key Exchange)
    ISAKMP - 키 교환 및 인증 프로토콜
모드
&nbsp; 터널모드 / New IP Header 이용
  전송모드 / IP Payload 보호
IPSec VPN, SSL VPN 비교
  OSI Layer - Layer 3 &lt;&gt; Layer 4 ~ 7 
  표준 - RFC 4301 &lt;&gt; RFC 5246 
  프로토콜 - IP &lt;&gt; TCP 
  인증방식 - 비밀키 공유 &lt;&gt; X.509 인증서 
  구현방식 - Site to Site (Lan to Lan) &lt;&gt; Client to Site 
  장점 - 높은 안정성 &lt;&gt; 브라우저 및 Agent 방식 구현 
  단점 - 고비용 &lt;&gt; 저비용
  사례 - 본사와 지사의 VPN 연결 &lt;&gt; 브라우저를 통한 기업 내부망 접속 

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
