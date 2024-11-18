---
title: FMEA
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
      I. 상향식 고장요인 분석기법, FMEA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. FMEA의 정의
        </div>
        <div class="para-cntnt">
            SW 안전성 분석위해 고장모드, 영향분석, RPN 계산 통해 분석하는 상향식 안전성 분석기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. FMEA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. FMEA의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/FMEA.png" alt="FMEA">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. FMEA의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  상향식 분석
  귀납적 기법
평가방법 심발검 RPN
  심각도 (Severity, S) - 설계적 문제, (1: 심각하지 않음, 10: 매우심각)
  발생도 (Probability of Occurrence, O) - 공정기술의 문제, (1: 발생빈도 매우 낮음, 10: 발생빈도 매우 높음)
  검출도 (Detection, D) - 관리력의 문제 (1: 검출가능성 높음, 10: 검출가능성 낮음)
  RPN (Risk Priority Number)
프로세스 메범도분영권
  범위, 대상 정의 - 분석 대상 및 범위를 명세서와 설계서, 매뉴얼 등을 활용하여 정의
  고장모드 도출 - 서브시스템 또는 기능을 나열하고 각각의 고장모드 도출
  고장모드 분석 - 고장모드의 발생도(Frequency)와 심각도(Severity), 원인을 파악
  영향 분석 - 고장모드가 시스템에 미치는 영향을 정의 및 평가
  권고사항 도출 - 각 고장모드에 의한 시스템 위험을 줄이기 위해 권고사항 도출
유형 제설공시
  제품 FMEA - 개발초기, 상품기획, 설계단계에서 설계되는 시스템 분석
  설계 FMEA - 생산단계 직전에, 설계된 제품의 기능 분석
  공정 FMEA - 생산단계에서 생산공정 분석
  시스템 FMEA

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
