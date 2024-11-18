---
title: 카나리 테스트
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
      I. 리스크 최소화, Canary Test 개념
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 카나리 테스트의 정의
        </div>
        <div class="para-cntnt">
            리스크 최소화 위해 소수 사용자에게 소프트웨어 선 출시하여 문제식별, 검증 테스트기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 카나리 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 카나리 테스트의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/카나리-테스트.png" alt="카나리 테스트">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 카나리 테스트의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          절차 사일문전
  사용자 선택 - 카나리아 테스트를 위해 소수의 사용자 또는 특정 사용자 세그먼트를 선택
  일부분 배포 - 이 사용자 그룹에 새로운 기능이나 업데이트를 배포하여 배포 프로세스가 원활하고 중단을 일으키지 않도록 함
  문제 식별 - 사용자 피드백, 분석, 오류 로그 및 기타 관련 데이터를 모니터링하여 발생할 수 있는 잠재적인 문제를 식별
  전체 배포 - 심각한 문제가 발견되지 않으면 전체 사용자 기반에 기능이나 업데이트를 출시
기술 피오로
  피처 플래그 - 새로운 기능 활성화 또는 비활성화
  오케스트레이션 - 컨테이너, CI/CD 배포
  로드밸런서 - 테스트 유저 분산
카나리 테스트, A/B 테스트 비교
  목적 - 안정성 평가 &lt;&gt; 비교 평가
  사용자 - 소수 사용자 &lt;&gt; 무작위 선택
  측정 - 성능, 오류 &lt;&gt; UX, 성과
- 심각결함 발생시 Rollback 안정성 제공

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
