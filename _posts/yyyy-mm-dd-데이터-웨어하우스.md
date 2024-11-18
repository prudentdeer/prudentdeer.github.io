---
title: 데이터 웨어하우스
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 데이터베이스]
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
      I. 데이터 웨어하우스
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 웨어하우스의 정의
        </div>
        <div class="para-cntnt">
            의사결정에 도움을 주기 위해 데이터를 공통형식으로 변환하여 관리하는 데이터관리 아키텍처
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 데이터 웨어하우스
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 웨어하우스의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/데이터-웨어하우스.png" alt="데이터 웨어하우스">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 데이터 웨어하우스의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징 주통시비
  주제중심적 / 통합적 / 시계열적 / 비휘발성
구성요소 오디오디메이
  ODS - 시간에 민감한 의사결정을 위한 특정 비즈니스 중심적인 현재 데이터 저장소
  DW - DB 어플리케이션 중립적이며 공유 환경인 데이터 저장소
  DM - 특정 어플리케이션 중심적, 특정 비즈니스 또는 부서 중심적 
  OLAP - 최종 사용자, 다차원 정보, 직접 접근, 대화식으로 정보분석, 의사결정
  ETL/ETT - Data를 운영계 시스템에서 추출, 변환, DW 적재
  메타데이터 - 전통적인 데이터 자원내의 데이터 요소들에 대한 정의 집합
Top Down 구축 vs Bottom-up 구축 vs Hybrid 구축
  관점 - 전사관점 / 특정부서, 일부그룹 / 혼합방식
  구축 - DW &gt; DM / DM &gt; DW / 병행구축
  장점 - 구현용이 / 시간, 비용절약 / 자원과 인력 분산투입
  단점 - 시간, 비용소모 / 구현후 문제발생소지 / -
- 데이터의 양과 종류가 빠르게 증가해 레이크 필요성

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
