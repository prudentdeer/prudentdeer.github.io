---
title: 손실함수
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
      I. 손실함수
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 손실함수의 정의
        </div>
        <div class="para-cntnt">
            신경망 최적 가중치를 찾기위해 알고리즘이 예측한 값과 실제 정답의 차이를 비교하기 위한 함수
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 손실함수
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 손실함수의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/손실함수.png" alt="손실함수">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 손실함수의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          사용목적
  신경망에서 가중치와 편향을 최적화 할 때 손실함수의 값을 가능한 작게 하는 값을 찾는다
  이때 미분(기울기)을 활용하고, 그 미분 값을 단서로 가중치와 편향 값을 서서히 갱신
손실함수의 종류 회분 평평교미
  회귀모형
    평균제곱 오차 - 각 원소의 출력과 정답 레이블의 차의 제곱에 평균을 취한 것 / MSE (Mean Squared Error)
    평균제곱근 오차
  분류모형
    교차 엔트로피 오차 - 정답이 아닌 출력 노드의 레이블 값은 0이므로 정답일 때의 출력만 전체 손실 값을 정하는데 사용
    미니배치학습 - 전체 데이터에서 일부를 랜덤으로 선별하여 근사치 값을 구한다. 선별된 일부 데이터를 미니배치(mini-batch)라 한다

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
