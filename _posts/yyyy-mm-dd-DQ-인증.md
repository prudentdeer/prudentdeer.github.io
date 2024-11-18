---
title: DQ 인증
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
      I. 양질 데이터의 유통생태계 조성, 데이터 품질인증
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DQ 인증의 정의
        </div>
        <div class="para-cntnt">
            데이터의 내용, 구조를 포함한 관리체계 등을 진단하고 수준을 평가해 품질 인증하는 제도
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DQ 인증
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DQ 인증의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DQ-인증.png" alt="DQ 인증">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DQ 인증의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          법적근거 데데이공
  데이터 산업진흥법 제 20조
심사항목 완유일 값레 구의범관 참
  완전성
    값 완전성 – 데이터 명세 등에 Notnull 조건 있는경우
    레코드 완전성 – 반정형은 레코드를 정의할 수 있는 경우
  유효성
    구문 유효성 – 구문의 정확성이 요구되는 경우
    의미 유효성 – 해당 필드 또는 속성에 의미상으로 유효한 리스트 존재하는 경우
    범위 유효성 – 명세서 등에 범위(숫자)가 정의된 경우
    관계 유효성 – 명세서 등에 의미론적 업무규칙이 정의된 경우
  일관성
    참조무결 일관성 – 명세서 등에 참조무결성이 정의된 경우
인증등급
  A 등급 - 필수심사 항목 전체, 선택 3개이상 통과  
  B 등급 - 필수심사 항목 전체 통과
  C 등급 - 필수심사 항목 일부 통과

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
