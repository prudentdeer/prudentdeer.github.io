---
title: OWASP Top 10(2021)
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 필수암기]
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
      I. 2021 OWASP Top 10
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. OWASP Top 10(2021)의 정의
        </div>
        <div class="para-cntnt">
            웹 애플리케이션 취약점 중 고빈도, 고영향의 10가지 선정하고, 대응방안 제공하는 기술 가이드
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. OWASP Top 10(2021)
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. OWASP Top 10(2021)의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/OWASP-Top-10(2021).png" alt="OWASP Top 10(2021)">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. OWASP Top 10(2021)의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          내용 접암인설보 취식소모서
  A01, 취약한 접근통제 - 서비스별 권한 / 최소권한부여 / ACL 적용 / WhiteList 
  A02, 암호학적 실패 - 데이터 암호화 저장 / 최신 알고리즘 / Salt 
  A03, 인젝션 - 명령어, 쿼리 분리 / 파라미터 검증 / 라이브러리 검증
  A04, 안전하지않은 설계 - Secure by Design / 위협 모델링 / 가상침투
  A05,&nbsp;보안설정 오류 - 샘플페이지 제거 / 오류페이지 별도 / 불필요기능 제거
  A06, 취약하고&nbsp;오래된 요소 - 패치관리 / 구성변경 모니터링 / CVE 모니터링
  A07,&nbsp;식별&nbsp;및&nbsp;인증실패 - MFA 다중인증 / 비밀번호 취약성검사 / FIDO / 기본계정 변경
  A08, SW 및&nbsp;데이터무결성&nbsp;실패 - SBOM / PMS 일괄배포 / 서명 검증 / 사전무결성 체크
  A09, 모니터링, 보안로깅 실패 - SIEM / SOAR / 모니터링 / 경고 / 분산로깅 
  A10,&nbsp;서버사이드&nbsp;요청위조, SSRF - 방화벽 관리 / Secure OS / 보안조직 / 화이트리스트

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
