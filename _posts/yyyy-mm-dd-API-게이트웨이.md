---
title: API 게이트웨이
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
      I. MSA 아키텍처 구현을 위한 API Gateway 개념
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. API 게이트웨이의 정의
        </div>
        <div class="para-cntnt">
            API 서버 앞단에서 API 인증, 인가, 로드밸런스, 추상화 역할을 수행하는 단일지점 처리 게이트웨이
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. API 게이트웨이
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. API 게이트웨이의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/API-게이트웨이.png" alt="API 게이트웨이">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. API 게이트웨이의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          주요기능
  보안
    인증 및 인가 - 클라이언트 인증 후 API 토큰 생성 및 발급
    API 호출 로깅 - 다양한 루트별 호출 로그 공통 관리 기술
  라우팅 
    엔드포인트 - 서비스 및 클라이언트별 엔드포인트 제공
    로드밸런싱 - 서버 부하 감지 및 여러 API 서버 트래픽 분산
  메디에이션
    메시지 포맷 변환 - 클라이언트-서버 간 다른 메시지 포맷 사용 시 변환
    프로토콜 변환 - 각 서비스 및 클라이언트 사용 통신 프로토콜 변환
  기타
    API Aggregation - 여러 개의 API 를 묶어 하나의 API 로 제공
    API Metering &amp; Charging - 유료 API 서비스 위한 과금 측정 기록 및 금액 계산
서비스 메시 vs API Gateway
  적용위치 - 서비스 그룹 내부 &lt;&gt; 외부
  라우팅 주체 - MS &lt;&gt; 서버
  구성요소 - 서비스 내 sidecar &lt;&gt; 독립적인 gateway 
  로드밸런싱 - 클라이언트 sidecar &lt;&gt; 단일엔드포인트 
  네트워크 - 내부서비스 사이 &lt;&gt; 외부인터넷과 내부 서비스 사이

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
