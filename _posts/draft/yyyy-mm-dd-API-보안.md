---
title: API 보안
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 디지털서비스]
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
      I. API 통신 무결성 확보, API 보안의 개념
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. API 보안의 정의
        </div>
        <div class="para-cntnt">
            웹앱간 안전한 통신을 위해 내외부 공격으로부터 API 및 송수신 데이터를 보호하는 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. API 보안
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. API 보안의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/API-보안.png" alt="API 보안">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. API 보안의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          위협
  취약한인증
    손상된 객체 수준 인증 - 객체 수준 권한 검사 미흡
    손상된 사용자 인증 - 인증 토큰 손상, 구현 결함 악용
    손상된 기능 수준 인증 - 관리기능, 일반기능 불분명하게 분리
  데이터노출
    과도한 데이터 노출 - 민감 데이터의 충분하지 않은 필터링
    인젝션 공격 - 악의적 SQL 입력으로 인한 데이터 노출
    대량 할당 - 대량할당 시 데이터 노출 수준과 민감도 미고려
  미흡한관리
    보안설정 오류 - 보안누락, 민감데이터 처리 메시지 오류 등
    부적절한 자산관리 - 엔드포인트 API 취약점 노출
    불충분한 로깅 및 모니터링 - 충분한 보안 가시성 미확보
대응방안
  인증강화
    인증 유효성 검사 - Referer Header 유효성 검사, ACL/CL/SL
    인증 매커니즘 강화 - 강력한 인증 수단 적용, MFA/OAuth 2.0
  데이터
    포맷 필터링 - 불필요한 데이터 노출 제어, 암호화/시큐어코딩
  노출제한 
    HTTP 요청 검사 - JSON 응답 클로킹(Cloaking), JSON 요청 필드 검사
  관리강화
    가시성 확보 - 보안 test, 취약점 모니터링, 스캐닝도구, 시각화
    엔드포인트 추적 - 접속가능한 API 엔드포인트 식별 및 추적

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
