---
title: 프로젝트 형상관리
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 프로젝트관리]
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
      I. SW 에 추적성과 가시성부여, 형상관리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 프로젝트 형상관리의 정의
        </div>
        <div class="para-cntnt">
            SDLC 과정의 단계별 산출물을 관리하여 가시성과 추적성을 부여, 품질을 향상시키는 관리 방법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 프로젝트 형상관리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 프로젝트 형상관리의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/프로젝트-형상관리.png" alt="프로젝트 형상관리">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 프로젝트 형상관리의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          필요성
  통제의 어려움 / 추적의 어려움 / 가시성 결핍
구성요소 형식통감기
  형상관리계획수립 - 형상관리 계획수립 / 형상관리 계획서
  형상식별 - 형상관리 항목 대상 구분 및 형상번호 부여 / 베이스라인 (기준선), 관리 체계
  형상통제 - 형상목록 변경요구 검토 및 승인 / 변경 요청서, 승인서, 검토결과
  형상감사 - 단계별 기준선, 베이스라인의 무결성 평가 / V&amp;V, 계획서, 보고서
  형상기록 - 변경내용 기록 및 도구에 의한 관리, 보고 / CMDB, 상태 기록문서,  상태 보고서
형상관리 도구
  중앙집중형 (CVS, Central Version Control System)
    CVS - 중앙에 위치한 Repository에 파일을 저장하고 모든 사용자가 접근 가능하도록 설계
    SVN - 최초 1회에 한해 파일 원본 저장, 이후에는 원본과 차이점을 저장
  분산형 (DVCS, Division Version Control System)
    GIT - 서버 저장소와 개발자 저장소가 독립적, 분산 버전제어 시스템
    GOGS

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
