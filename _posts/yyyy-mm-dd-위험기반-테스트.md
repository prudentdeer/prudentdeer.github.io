---
title: 위험기반 테스트
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
      I. 비즈니스 중요도가 높은 영역 중심의 리스크 기반 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 위험기반 테스트의 정의
        </div>
        <div class="para-cntnt">
            발생가능성과 영향력을 평가하여 중요도 중심으로 테스트하여 리스크를 최소화하는 테스트
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 위험기반 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 위험기반 테스트의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/위험기반-테스트.png" alt="위험기반 테스트">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 위험기반 테스트의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          절차 식분대전추
  위험식별 - 발생 가능한 위험의 카테고리화 / Risk ITEM
  위험분석 - 식별된 위험의 정량적 분석 (발생가능성, 영향도) / 위험, 영향 Metric
  대응계획 - 위험항목별 회피, 전가, 완화, 수용의 최소화 대응계획 수립 / 위험대응목록
  전략수립 - 대응계획에 충족하는 테스트 종료결정, 완료조건, 목표수준 정의 / Master Test Plan
  위험추적 - 리스크 및 리스크에 대한 대응을 모니터링 / 위험관리대장
전략 영가 서스인펀
  STA - 반드시 테스트 해야 함
  STTA - 테스트 해야 함
  ITA - 테스트 함  
  FTA - 테스트 안해도 됨

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
