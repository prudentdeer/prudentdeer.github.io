---
title: SW 안전
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
      I. SW 안전
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SW 안전의 정의
        </div>
        <div class="para-cntnt">
            SW 내/외부 오작동, 기능미비로 발생가능 사고로부터 신체, 생명 위험에 대비되어 있는 상태
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SW 안전
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SW 안전의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SW-안전.png" alt="SW 안전">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SW 안전의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          필요성
  SW 복잡/다양화 &gt; 생활밀접화 &gt; 피해발생 증가
  Safety-critical 분야 SW 역할 점점 커지고 있음
상세내용 보발미시국
  보호대상 - 사람의 신체, 생명, 재산
  발생원인 - 설계 오류, 검증 누락
  미충족 결과 - 사람 상해, 재산 손실
  시스템 - 항공관제시스템, 열차제어시스템
  국제표준 - IEC 61508
분석방법 포메하이스
    FTA / 연역, 하향식 - 정상사상, 기본사상, 통상사상, And, Or, Gate 포범고전분, 사게이분
    FMEA / 귀납, 상향식 - RPN(심각도, 발생도, 검출도) 메범도분영권, 심발검 RPN
    HAZOP / 탐색, 상향식 - 공정변수, 가이드워드, 이탈상황 하범이영위, 공가이
    ETA / 귀납, 상향식 - 귀납분석, 초기 오류 대처 이범사이트결
  시스템이론 기반 
    STPA / STAMP - 생명주기, 사람, 정책, 환경고려 사정환 사위씨유원
진단영역 안품기
  안전기능 충분성 - 시스템 잠재 위험 분석 / 위험원 감지, 회피, 제거
  SW품질 안전성 - 주요 기능 정상 동작 / 안전 관련 기능 정상 동작
  기반SW 안전성 - 기반SW 지속운영 진단 / 운영체제, DB 등 기반 SW 정상 동작 진단

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
