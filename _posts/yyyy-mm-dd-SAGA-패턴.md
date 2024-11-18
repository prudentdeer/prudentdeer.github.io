---
title: SAGA 패턴
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
      I. MSA의 원자성 보장, SAGA 패턴
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SAGA 패턴의 정의
        </div>
        <div class="para-cntnt">
            MSA 환경에서 데이터 일관성 유지를 위해 비동기 메시징을 이용해 원자성을 보장하는 패턴
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SAGA 패턴
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SAGA 패턴의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SAGA-패턴.png" alt="SAGA 패턴">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SAGA 패턴의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형
  Choreography 
    정의 - 중앙 집중식 제어지점 없이 마이크로서비스가 보상트랜잭션을 결정하고 처리하는 방식
    장점 - 간단한 워크플로에 적합 / 구현이 용이함
    단점 - 순환종속오류 발생 / 현재 트랜젝션 상태 알기 어려움
  Orchestration
    정의 - 중앙 오케스트레이터를 사용해 실행 순서를 정의하고 필요한 보상 작업을 트리거함
    장점 - 복잡성 감소 / 롤백 용이
    단점 - 조정논리 구현필요 / SPF 문제발생

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
