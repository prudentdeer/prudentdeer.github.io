---
title: 데이터 프로파일링
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
      I. 데이터 값 진단, 데이터 프로파일링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 프로파일링의 정의
        </div>
        <div class="para-cntnt">
            메타데이터 통한 데이터 규칙기반으로 데이터의 비일관성, 통계값, 오류 등을 수집하는 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 데이터 프로파일링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 프로파일링의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/데이터-프로파일링.png" alt="데이터 프로파일링">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 데이터 프로파일링의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          주요대상 관구활
  데이터 관리영역 - 분류 체계, 데이터 표준 및 관리 정책
  데이터 구조영역 - 모델, 도메인 속성 및 제약조건, 테이블/컬럼/Occurrence
  데이터 활용영역 - 데이터 흐름, 연관성, 사용현황 (조회건수, 사용자)
프로세스 메규확검결
  메타데이터 수집 / 형상관리 - 테이블 및 컬럼 정의서, 도메인 정의서, ERD
  규칙발견 및 도출 / 패턴도출 - 패턴을 적용하여 분석, 규칙 도출
  규칙확정 / 속성규칙 - 단일 컬럼의 속성규칙, 비즈니스 요구사항에 따른 규칙
  데이터검증 / 오류검출 - 실제 규칙 위배 오류데이터 추출
  결과리뷰 / 품질개선 - 지속적 데이터 품질 개선을 위해 원인분석과 개선과정
기법 컬구 단복값
  컬럼속성 분석 - 하나의 컬럼에 저장된 값 분석
  구조분석 - 테이블을 구성하는 컬럼 간의 관계분석
  단순데이터 룰 분석 - 값의 결합이 가능한 비즈니스 객체의 여러 컬럼 걸친 값 분석하여 데이터 정제
  복잡데이터 룰 분석 - 여러 비즈니스 객체에 연관된 복잡한 데이터 룰을 분석
  값룰 분석 - 집계 값을 통하여 부정확한 데이터의 존재는 찾는 것

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
