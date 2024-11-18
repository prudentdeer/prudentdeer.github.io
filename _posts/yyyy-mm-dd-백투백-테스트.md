---
title: 백투백 테스트
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
      I. 테스트 이중화, 백투백 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 백투백 테스트의 정의
        </div>
        <div class="para-cntnt">
            두개 이상의 시스템을 동일한 입력값 실행하여 결과비교하고, 불일치시 서로 비교분석하는 테스트
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 백투백 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 백투백 테스트의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/백투백-테스트.png" alt="백투백 테스트">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 백투백 테스트의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  높은 신뢰성 : 결함발생 가능성 최소화
  설계명세 기반 : 설계 - 구현 결과 정확성 체크
절차
  테스트케이스 생성 - 수행 될 테스트 케이스를 작성
  테스트 수행 - 테스트 대상에 대한 병렬수행
  테스트 결과확인 - 테스트 결과값 동일여부 비교
  테스트 결과분석 - 불일치 시 결과 원인 분석
방법
  요구조건, 인터페이스, 모델코드
활용
  제어모델과 소스코드 간 품질 검증
  단위/통합/시스템 테스트 수행 시 주요 검증 방법으로 권고(ASIL 수준별)
  ISO26262, DO-178(B,C)
  프로토타입 또는 회귀테스트에 사용가능

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
