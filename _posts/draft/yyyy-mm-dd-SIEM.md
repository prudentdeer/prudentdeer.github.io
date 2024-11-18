---
title: SIEM
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
      I. SIEM = SIM (보안정보 관리) + SEM (보안이벤트 관리)
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SIEM의 정의
        </div>
        <div class="para-cntnt">
            다양한 보안위협에 대해 이벤트 수집 및 분석을 통해 탐지, 대응이 가능한 지능형 보안기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SIEM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SIEM의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SIEM.png" alt="SIEM">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SIEM의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          프로세스
  DataSource
    로그분석 - 시스템 로그, 이벤트, 감사 로그, 사용자 활동 분석
    데이터 감시 - DPI, 패킷 캡쳐, 파일 및 시스템 활동 감시
  MachineAnalysis
    데이터표준화 - Input 데이터 전처리, ML 모델에 적용, 패턴 매칭
    이상행위 탐지 - 비정형 및 상황 기반 이상행위 탐지, Drill-down 분석
  Result
    위협 분석 보고 - Dashboard, Report, 사용자 경보
    위협 대응 자동화 - 자동 차단, 사고 추적, 증거 보존

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
