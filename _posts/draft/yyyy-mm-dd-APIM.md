---
title: APIM
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
      I. API 관리시스템, APIM의 개요
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. APIM의 정의
        </div>
        <div class="para-cntnt">
            API 관리 인터페이스, 모니터링 통해 효율적인 API 관리환경 제공하는 중앙집중식 관리시스템
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. APIM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. APIM의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/APIM.png" alt="APIM">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. APIM의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  API 게이트웨이
    변환엔진 - API 요청, 응답을 조정 및 수정
    보안 - API 호출제어, API 전송데이터 위변조 방지, API 사용 인증 등
    로드밸런싱 - 백엔드의 복수의 API 서버에 트랜잭션의 분산처리
    오케스트레이션 - 다수의 API를 조합하여 새로운 복합 API 를 조합
  API 포털
    문서화 - API 목록, 명세등을 등록, 검색, RAML, OAS3.0 사용
    사용자 등록 - 역할기반으로 사용자 등록가능, 접근제어 기능 제공
    분석 - API 사용현황, 과금정책, 기간별 사용현황 분석
    커뮤니티 - API 생태계를 지원하기 위한 관련 개발자 소통도구
  API 서버
    API 요청 처리 - API Gateway 의 요청을 받아 처리 후 전달
  API 저장소 
    API repository - API 등록 후 수정, 변경, 삭제 등을 처리하는 저장소

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
