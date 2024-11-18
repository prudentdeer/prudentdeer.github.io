---
title: 역전파
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
      I. 인공신경망의 가중치 학습 최적화, 역전파 알고리즘
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 역전파의 정의
        </div>
        <div class="para-cntnt">
            인공신경망 출력오차 개선하기위해 역방향 오차 전파, 가중치 갱신하는 반복 알고리즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 역전파
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 역전파의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/역전파.png" alt="역전파">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 역전파의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  반복수행, 다층신경망, 감독학습, 역방향 계산
학습절차 피오가반
  피드포워드 / 가중치 초기화 - 입력층 &gt; 출력층으로 순전파 수행
  오류역전파 계산 / 미분 (예상값-실제값) - 출력층에서부터 역방향 진행
  가중치 조정 / 옵티마이저 - 학습률만큼 수정한 가중치로 조정
  반복 수행 / N회 epoch - 목표 도달 시 까지 위 과정 반복
  - 다층 신경망에서 경사하강(Gradient Descent)을 수행하는 핵심 알고리즘
문제점
  기울기 소실 문제 (Vanishing gradient problem) 발생
해결방안 롱디렐리 
  학습측면
    LSTM - 메모리기억 장기의존성 문제 해결
    DBN - 파인튜닝 이전 사전학습
  활성함수
    ReLU - 미분값의 보존
    Leaky ReLU - 음의 값 활용

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
