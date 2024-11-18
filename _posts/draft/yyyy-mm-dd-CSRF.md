---
title: CSRF
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
      I. CSRF
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CSRF의 정의
        </div>
        <div class="para-cntnt">
            클라이언트가 의도와 무관하게 자기권한으로 변조요청을 서버에 강제하는 공격기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. CSRF
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CSRF의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/CSRF.png" alt="CSRF">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. CSRF의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          공격 매커니즘
  공격코드등록 / html tag, javascript - 공격 스크립트가 포함된 링크 전달 혹은 게시물 등록
  페이지요청 / 피해자 열람 - 피해자는 공격 스크립트를 열람, 로그인 수행
  서버응답수행 / 공격코드 전송  - 서버에서 공격 스크립트에 대한 응답 데이터 전송
  위조요청전송 / 변조요청  - 인가된 정상 사용자로 조작된 요청 전송
대응방안 토레쿠포
  백엔드
    CSRF 토큰사용 - Spring security, Django 예측 불가능한 토큰값을 매 요청 인증시 사용
    Referrer 검증 - http 헤더의 URL 검사  
  프론트엔드
    Samesite coockie - 쿠키 생성도메인만 쿠키사용 설정 
    POST 방식사용 - GET 방식은 캐싱, 변조위험
CSRF 와 SSRF 비교
  변조 - 클라이언트 &lt;&gt; 웹서버
  공격대상 - 서버 &lt;&gt; 내부 리소스
  공격방법 - 취약점 연계공격 &lt;&gt; 오동작, 정보탈취
  방어기법 - CSRF 토큰, referer 검사 &lt;&gt; 입력 필터링, 외부 접근제한 등
- CSRF는 GET/POST 모두 가능하므로 복합적 방어필요

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
