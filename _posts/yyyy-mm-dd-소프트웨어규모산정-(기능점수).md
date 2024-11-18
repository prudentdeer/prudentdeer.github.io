---
title: 소프트웨어규모산정 (기능점수)
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
      I. 비용산정위한, 소프트웨어 규모산정
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 소프트웨어규모산정 (기능점수)의 정의
        </div>
        <div class="para-cntnt">
            실행가능 계획수립 위해 소프트웨어 소요공수, 투입자원, 소요기간 통해 규모파악 산정기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 소프트웨어규모산정 (기능점수)
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 소프트웨어규모산정 (기능점수)의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/소프트웨어규모산정-(기능점수).png" alt="소프트웨어규모산정 (기능점수)">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 소프트웨어규모산정 (기능점수)의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          SW 규모산정 어려움
&nbsp; 소프트웨어 비가시성
  잠재영향요소 많음
  기술 및 환경 의존성
  신기술&nbsp;등장
필요성
  낮게 산정 시 - 품질문제 발생, 납기문제, 개발자 부담 가중
  높게 산정 시 - 예산낭비(개발비, 유지보수비), 일의 효율성 저하
기능점수 = 규모 산정방식 라맨전델코펑
  상향식 
    LOC - 코드 라인수의 비관적, 낙관치, 기대치를 측정하여 예측치 이용해 비용 산정방식
    MM - 프로젝트 투입 인원, 레벨별 비용 산정방식
  하향식
    전문가감정 - 경험이 많은 두 명 이상의 전문가에게 비용 산정을 의뢰하는 기법
    델파이 - 전문가감정 주관적인 편견을 보완위해 많은 전문가의 의견을 종합산정기법
  수학식
    COCOMO - 모듈과 서브시스템의 비용합계를 계산하는 방식
    COCOMO2 - 기존 COCOMO 수정하고 ADA COCOMO 통합한 기법
    FP - 사용자관점에서 측정된 소프트웨어기능의 양으로서 SW 규모를 측정하기위한 표준기법
고려사항
  프로젝트 
    복잡도 - 난이도, 유형, 개발언어
    시스템규모 - 트랜잭션(입력, 출력), 데이터 연계
  자원 
    인적자원 - 관리자, 개발자, 지원체계
    물적자원 - 개발지원 도구, 테스트 툴
  생산성
    개발자능력 - 경험, 전문지식 습득 정도
    개발방법론 - 최신기법, 개발 방법론, 관리 방법론
- SW 비가시성 극복하고 계획수립위해 규모산정이 중요함

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
