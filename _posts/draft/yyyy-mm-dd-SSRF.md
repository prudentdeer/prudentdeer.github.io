---
title: SSRF
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
      I. SSRF
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SSRF의 정의
        </div>
        <div class="para-cntnt">
            외부에 노출된 웹서버의 요청을 변조해 내부서버와 자원 요청강제, 정보유출 공격기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SSRF
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SSRF의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SSRF.png" alt="SSRF">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SSRF의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          절차
  요청조작 - 웹 취약점 이용한 서버에 대한 요청 조작
  내부서버전달 - 서버는 조작된 요청 피해 서버에 전달
  요청수행 - 피해 서버는 서버의 요청에 따라 실행
  정보유출 - 공격자는 피해 서버 접근 또는 정보 유출
대응방안 입최모개
  입력값 검사 - 사용자의 입력값을 검사하여, 제공하는 서비스만 이용
  최소권한 사용 - 운영 준비 단계에서 IAM 권한에 대한 점검이 필수로 수행돼야 합니다.
  모니터링 - SSRF 공격 징후를 탐지할 수 있는 접속 기록
  개발보안 - 개발 초기 단계부터 보안을 고려하며 설계
CSRF 와 SSRF 비교
  변조 - 클라이언트 &lt;&gt; 웹서버
  공격대상 - 서버 &lt;&gt; 내부 리소스
  공격방법 - 취약점 연계공격 &lt;&gt; 오동작, 정보탈취
  방어기법 - CSRF 토큰, referer 검사 &lt;&gt; 입력 필터링, 외부 접근제한 등
- CSRF는 OWASP TOP 10:2021 에 선정됨

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
