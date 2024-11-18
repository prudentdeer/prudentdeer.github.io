---
title: Oauth 2.0
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
      I. 서비스 인증과 권한부여, OAuth 2.0
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Oauth 2.0의 정의
        </div>
        <div class="para-cntnt">
            Access Token을 통해 3rd party 리소스에 대한 접근 권한 및 인증을 위한 범용적인 인증 표준
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Oauth 2.0
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Oauth 2.0의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Oauth-2.0.png" alt="Oauth 2.0">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Oauth 2.0의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          절차 요승요발요제
  권한요청 - 클라이언트는 자원 소유자에게 접근 권한 요청
  권한승인 - 클라이언트에게 자원에 대한 접근 권한을 승인
  Access Token 요청 - 클라이언트가 권한 서버에게 접근 토큰을 요청
  Access Token 발급 - 권한 검증 및 Access Token 발급, 토큰 유효기간 만료 시 refresh token 추가 발급
  자원요청 - Access Token으로 자원 서버에게 인증 및 자원요청
  서비스 제공 - Access Token 검증 및 서비스
권한부여방식 4가지 PICA
  Password Credencials - ID, Password로 바로 토큰 발급
  Implicit - 추가절차 없이 Owner가 인증 및 허가하면 토큰 발급
  Client Credential - Client ID / Secret 정보로 토큰 발급
  Authorization Code - 사용허락 증서인 권한코드로 토큰 요청
Oauth 1.0과 2.0의 비교
  역할 명칭 - 이용자 &lt;&gt; 자원소유자
                    소비자 &lt;&gt; 클라이언트
                    서비스 제공자&lt;&gt; 자원서버, 권한서버
  인증 및 서명 - ID, PW 암호화 요구 &lt;&gt; HTTPS(SSL/TLS) default
  SSL 사용여부 - 미사용 &lt;&gt; 사용(TLS 1.0~1.3 적용)
  개발 및 권한 부여 흐름 - 웹 브라우저 적합 &lt;&gt; 웹, 모바일 콘솔 등 추가 환경 지원
  규모 성능 - API서버가 ID, PW 인증을 위해 직접 &lt;&gt; 인증서버, API서버 분리

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
