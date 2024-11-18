---
title: 사이버대피소
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
      I. 중소기업을 위한 무료솔루션, 사이버대피소
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 사이버대피소의 정의
        </div>
        <div class="para-cntnt">
            중소기업 기본법 2조에 의거 KISA 에서 중소기업에게 제공하는 무료 DDOS 방어 솔루션
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 사이버대피소
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 사이버대피소의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/사이버대피소.png" alt="사이버대피소">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 사이버대피소의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          기술요소 아화디로
  관리적 측면
    IP 차단 - 60초 기준 1개 IP에서 같은 URL을 100회 요청시 60분간 차단되며, 임계치 임의 수정 가능
    WhiteList 관리 - 관리자 IP 혹은 지속적으로 요청이 많은 정상적인 URL 및 IP 기반의 예외 설정
  기술적 측면
    DNS 정보변경 - DNS CNAME처리 또는 DNS A Record 변경 통해 해외에서 유입되는 트래픽의 차단
    로드밸런싱 - Least Connection 방식의 Load Balancing 기술 적용
스크러빙 센터와 사이버 대피소
  대상 - 클라우드환경, 온프레미스 환경  &lt;&gt; 웹사이트
  방법 - 트래픽 우회 &lt;&gt; 중소, 영세기업 대상 디도스 차단
  주체 - 일반 보안기업 &lt;&gt; KISA
  특징 - Tbps 이상 대용량 &lt;&gt; 중소기업 누구나 사용가능
  방식 - AI 학습 실시간 차단, 신규공격 대응 &lt;&gt; DNS 변경만으로 방어서비스 제공
- 사이버 대피소 시스템은 본래 웹 서버 IP와 연결돼 있던 A라는 도메인을 대피소 IP와
 연결되도록 DNS의 정보를 조정한다. 이로써 트래픽을 대피소로 우회시킨다.

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
