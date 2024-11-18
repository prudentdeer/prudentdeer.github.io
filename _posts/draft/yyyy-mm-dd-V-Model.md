---
title: V-Model
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
      I. SDLC 에 따른 테스트 모델, V-Model
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. V-Model의 정의
        </div>
        <div class="para-cntnt">
            SDLC 각 단계별 명세화 된 기능을 올바로 수행하는지 확인하기 위한 검증/확인 위한 테스트 모델
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. V-Model
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. V-Model의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/V-Model.png" alt="V-Model">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. V-Model의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  추적성 보장 - 각 테스트 단계에서 어떠한 단계에서 발생한 오류인지 추적성을 보장
  확장성 - 소프트웨어 개발 프로세스인 폭포수 모델의 확장된 형태
  신뢰성 - 높은 신뢰성이 요구되는 소프트웨어에 적용
유형 분설상코 단통시인
  단위 테스트 - 구현 단계에서 프로그램 개발자에 의해 수행
  통합 테스트 - 모듈을 결합, 한 시스템으로 구성하여 테스트 수행
  시스템 테스트 - 비기능적 테스트 (신뢰성, 견고성, 성능, 안정성 등), 기능 확인
  인수 테스트 - 사용자의 만족 여부를 테스트하는 품질 테스트
Verification vs Validation
  관점 - 개발자 시각 &lt;&gt; 사용자의 시각
  대상 - 제품 생산과정 &lt;&gt; 생산된 제품결과
  기간 - 각 단계별 &lt;&gt; 시작과 종료

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
