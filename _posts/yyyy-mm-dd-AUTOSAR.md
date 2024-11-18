---
title: AUTOSAR
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
      I. 자동차 전장 소프트웨어 플랫폼, AUTOSAR
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. AUTOSAR의 정의
        </div>
        <div class="para-cntnt">
            자동차의 성능과 편의성 향상을 위해 ECU의 효율성과 소프트웨어 재사용을 위한 개방형 소프트웨어
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. AUTOSAR
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. AUTOSAR의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/AUTOSAR.png" alt="AUTOSAR">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. AUTOSAR의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징 &nbsp; &nbsp;
  하드웨어와 소프트웨어 분리, 모델기반 개발 방법론, XML 문서로 상호연결  
구성요소
  SWC (Software Component)
    Port Interface - 외부 시스템 및 다른 SWC와 상호 작용하기 위해 포트 인터페이스 정의
    Run-Time Information - SWC의 런타임 동작 및 상태를 관리하기 위한 정보
    Internal Logic - SWC 기능 실행하는 알고리즘 및 동작
  RTE (Run-Time Environment)
    SWC-Proxy - RTE와 SWC 간의 통신을 관리, SWC와 데이터 교환/호출
    RTE-Configuration - RTE의 설정 정보. SWC 및 포트 인터페이스, 포트와 연결된 통신 경로
    Diagnostic Event Manager - 진단 이벤트 처리. 자동차 상태 모니터링 및 진단 관리
  BSW
    Service Layer - 시스템 구동 및 다른 BSW 내 모듈의 전반적인 제어를 위한 서비스 제공
    EAL(ECU Abstraction Layer) - MCAL Driver의 인터페이스 제공, 추상화 계층
    MCAL(Microcontroller Abstraction Layer) - 마이크로 컨트롤러 내부 장치를 이용위한 Driver로 구성
    CDD(Complex Driver) - 특정 계층에 매핑 되지 않고 Microcontroller에서 RTE까지 직접 인터페이스

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
