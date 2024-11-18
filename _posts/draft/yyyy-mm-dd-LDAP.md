---
title: LDAP
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
      I. LDAP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. LDAP의 정의
        </div>
        <div class="para-cntnt">
            정보를 트리구조로 저장하여, 수정, 조회 등 디렉토리 서비스를 전달하는 응용프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. LDAP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. LDAP의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/LDAP.png" alt="LDAP">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. LDAP의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          LDAP 의 인증흐름 TBAP 티밥
  1 - TLS Request / Resp - LDAP 인증서버와 TCP 연결 구축
  2 - Bind Request / Resp - LDAP 서버의 프록시 계정으로 인증
  3 - Auth Request - 로그인 자격증명 인증요청
  4 - Password Request - 로그인 성공시 권한 부여
LDAP 이용한 통제정책 설계 디권티규
  디렉터리 구조설계 - 계층구조 정의하고 LDAP 디렉터리 설계
  접근권한 부여 - 필요한 정보에 대한 접근을 허용 
  TLS/SSL 설정 - 통신 내용을 암호화하여 보안을 강화합니다.
  접근규칙 설정 - 필터를 사용하여 특정 범위의 정보에 대한 접근 제어
- 클라우드, SSO 이용한 클라우드 ldap 적용 

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
