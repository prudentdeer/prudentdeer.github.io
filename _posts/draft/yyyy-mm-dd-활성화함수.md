---
title: 활성화함수
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
      I. 인공신경망 입력변환, 활성화 함수
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 활성화함수의 정의
        </div>
        <div class="para-cntnt">
            입력값을 은닉층, 출력층으로 전달하기 위해, 일정범위 결합 값으로 변환하여 전달하는 함수
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 활성화함수
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 활성화함수의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/활성화함수.png" alt="활성화함수">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 활성화함수의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          대표유형
  단극성/양극성, 선형/비선형, 연속/이진
유형 항계시렐리탄
  항등함수 - 양극성이며 선형 연속 함수, 입력의 가중합이 그대로 출력됨
  계단함수 - 단극성 또는 양극성 이진 함수이며, 디지털 형태의 출력이 요구되는 경우
  시그모이드함수 - 단극성 또는 양극성 비선형 연속 함수이며, 신경망 모델의 활성화 함수
  ReLU - 입력값이 0보다 작으면 0, 입력값이 0보다 크면 입력값 그대로 (Rectified Linear Unit)
  Leaky ReLU - ReLU 음수값 0 문제를 해결위해 음에서 작은 기울기
  Tanh - 쌍곡 탄젠트 함수

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
