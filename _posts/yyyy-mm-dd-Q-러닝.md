---
title: Q-러닝
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 인공지능]
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
      I. 강화학습 기법, Q-러닝 
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Q-러닝의 정의
        </div>
        <div class="para-cntnt">
            행동에 대한 효용 Q값을 미리 계산하여, Q값을 최대화하는 최적정책을 찾는 강화학습 방법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Q-러닝
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Q-러닝의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Q-러닝.png" alt="Q-러닝">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Q-러닝의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          Q-러닝의 프로세스 초액수리갱
  Q 초기화 - Value table Q(상태, 액션) 초기화
  액션선택 - 액션 선택 정책에 기반하여 현재 상태에 맞는 액션 선택
  액션수행 - 새로운 상태와 보상에 대한 관찰
  리워드 업데이트 - 보상에 대한 관찰 및 다음 상태에서의 보상 최대치 업데이트
  Q 갱신 - 새로운 상태 설정 및 반복 수행
  - 보상에 의한 정책에 따라 액션을 수행하고, 보상의 측정 및 업데이트 수행
Q-러닝의 구성요소 정벨큐
  정책 / 최고보상, 미래보상 관찰 - 가장 높은 Q값을 가지도록 액션 선택 규칙
  벨만 방정식 / 정책반복, 재귀함수 - 최적의 정책을 찾기 위한 반복 수행, 현재 상태의 최고보상과 미래보상의 최대값 합계
  Q-러닝 알고리즘 / 테이블 기반, 반복적 근사 - 벨만 방정식의 반복수행으로 Q함수 근사 가능, 각 행은 상태에 해당하며, 각 열은 액션에 대응
  - 테이블 형태의 Q-러닝 알고리즘의 사이즈 문제에 대한 해결 방안으로 DQN 등장
Q-러닝 사이즈 문제 해결을 위한 DQN 사례
  ConvNet 활용 / 동작구성도 : 상태와 액션을 입력 받아 해당 상태와 액션의 Q 함수 값을 출력하는 신경망 정의
  - 신경망에서 손실함수는 제곱오차로 정의가능하며 테이블 형태의 Q-러닝 함수의 오차장의와 유사

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
