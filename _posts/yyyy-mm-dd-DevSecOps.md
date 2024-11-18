---
title: DevSecOps
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
      I. Security driven DevOps, DevSecOps
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DevSecOps의 정의
        </div>
        <div class="para-cntnt">
            개발과 운영의 융합과 협업을 통한 개발 주기에서 보안 측면의 주기를 포함하는 개발 방법론
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DevSecOps
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DevSecOps의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DevSecOps.png" alt="DevSecOps">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DevSecOps의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          적용범위
  Plan 보안 정책 관리 - Metric 관리, 보안 위협 모델링 수립, 플랫폼 교육 등의 계획 수립 
  Create 시스템 설계 - 공격 루트 최소화, 권한 설계, N/W 설계, 시스템 설계, k8s 설계 등 
  Verify 테스트 - SAST, DAST, IAST, SCA 등 애플리케이션의 테스트 및 분석 
  Preprod 배포 전 테스트 - 카오스 몽키, 퍼징, 통합 테스트 및 자동화 침투 봇 배치 테스트 
  Release 디지털 서명 - 소프트웨어, 애플리케이션의 SHA 등의 디지털 서명 
  Prevent 릴리즈 검증 - 디지털 서명 검증, Checksum 무결성 검사 등 심층 방어 조치 수립 
  Detect 공격 탐지 - 런타임 애플리케이션 자가 보안, 사용자 행동 분석, 내부 위협, FDS 등 
  Respond 런타임 위협 차단 - 보안요건 재검토 및 조정, RASP/WAF 등 런타임 환경 보안 위협 차단 
  Predict 예상 위협 예측 - 침입 흔적, 위협/위협 행위자 정보, 위협 정보 전송규격 등으로 예측 
  Adapt 보안 부서 - 보안 위협에 대응하는 보안 관제 등 부서

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
