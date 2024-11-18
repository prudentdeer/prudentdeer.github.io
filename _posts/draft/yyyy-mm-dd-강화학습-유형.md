---
title: 강화학습 유형
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
      I. 강화학습 유형
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 강화학습 유형의 정의
        </div>
        <div class="para-cntnt">
          가치기반
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 강화학습 유형
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 강화학습 유형의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/강화학습-유형.png" alt="강화학습 유형">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 강화학습 유형의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            정의 - 실제가치를 추정할 가치함수를 학습, 가치기반행동 선택하는 강화학습
  특징 - 정책함수 없음, 높은가치 행동선택
  알고리즘
    DQN - Q-Learning의 개념을 딥러닝에 적용
    DRQN - RNN 이용 시계열 개념적용
    DDQN - 두개의 네트워크 이용 (Double deep QN)

정책기반
  정의 - 주어진 상태에 대해 정책함수가 행동을 직접 선택하는 강화학습
  특징 - 확률분포 기반
  알고리즘 
    Reinforce - 정책 파라미터를 조정하여 보상의 기댓값을 최대화

액터크리틱 
  정의 - 정책함수 (액터)와 가치함수 (크리틱)을 함께 학습하는 강화학습
  특징 - 액터는 행동선택, 크리틱은 가치평가
  알고리즘 
    Q Actor-Critic - Q 함수를 사용하여 가치를 추정
    A2C - 정책과 가치함수 동시에 학습 (Advantage Actor-Critic)
    A3C - 비동기적 여러 에이전트가 병렬적 학습 (Asynchronous Advantage Actor-Critic)

정책경사 강화학습
정의
  정책을 모델링하여 최적화 위해 목적함수 기울기 계산하고, 기대보상을 최대화하는 강화학습
특징
  확률적 정책학습 - 상태에서 각 액션을 취할 확률 학습
  연속적 정책개선 - 최대화 보상방향으로 지속적 정책개선
  대규모 액션공간 - 연속적 액션공간 다룰 수 있음

https://dreamgonfly.github.io/blog/rl-taxonomy/

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
