---
title: 휴리스틱 오라클
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
      I. 샘플링 오라클 단점 개선, 휴리스틱 오라클
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 휴리스틱 오라클의 정의
        </div>
        <div class="para-cntnt">
            특정 입력 값에 대해 샘플링 오라클과 같은결과 제공, 나머지 입력은 휴리스틱 처리 테스트 오라클 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 휴리스틱 오라클
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 휴리스틱 오라클의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/휴리스틱-오라클.png" alt="휴리스틱 오라클">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 휴리스틱 오라클의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          프로세스
  1단계 / 휴리스틱 식별 - 테스터 경험, 도메인 지식 및 일반적 테스트 관행 기반
  2단계 / 휴리스틱 적용 - 경계값, 사용자 시나리오, 위험기반 우선순위 지정 요소 고려
  3단계 / 테스트 케이스 생성 - 특정 입력 및 출력, 시스템 동작 식별 
  4단계 / 테스트 실행 - 휴리스틱에 따라 결정된 예상 결과와 비교 
  5단계 / 결과 평가 - 테스트 실행 후 편차나 결함 발견 확인 

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
