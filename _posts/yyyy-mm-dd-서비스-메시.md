---
title: 서비스 메시
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 소프트웨어공학]
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
      I. 마이크로 서비스 간의 통신을 담당, 서비스 메시
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 서비스 메시의 정의
        </div>
        <div class="para-cntnt">
            MSA환경에서 호출제어 및 오버헤드 최소화 위해 Sidecar, Circuit breaker 이용 인프라계층
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 서비스 메시
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 서비스 메시의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/서비스-메시.png" alt="서비스 메시">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 서비스 메시의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 컨데사써서비
  아키텍처
    Control Plane - 중앙 집중화된 컨트롤러에서 Proxy 설정 정보 제어
    Data Plane - 서비스간 Proxy 통해 데이터 흐름 처리
  컴포넌트
    Sidecar Proxy - 서비스 인바운드/아웃바운드 트래픽 관리
    Circuit Breaker - 장애 상황 격리, 장애 전파 방지하여 시스템 안정성 및 신뢰성 향상
  비즈니스 
    Service Discovery - 서비스 시작 시 컨트롤러에 게시
    Business Logic - MicroService에서 수행되는 핵심 비즈니스 기능 수행
서비스 메시 vs API Gateway
  적용위치 - 서비스 내부 &lt;&gt; 외부
  라우팅 주체 - 요청하는 MS &lt;&gt; 서버
  구성요소 - 서비스 내 sidecar &lt;&gt; 독립적인 gateway 구성요소
  로드밸런싱 - 클라이언트 sidecar에서 &lt;&gt; 단일엔드포인트 에서
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
