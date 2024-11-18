---
title: RNN
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
      I. 순환 신경망, RNN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. RNN의 정의
        </div>
        <div class="para-cntnt">
            스스로 반복하며 입력 데이터와 과거 데이터를 고려하여 순차적 데이터 처리하는 순환 신경망
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. RNN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. RNN의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/RNN.png" alt="RNN">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. RNN의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  과거-미래 영향 구조 : 루프 구조를 통해 과거의 데이터가 미래에 영향을 줄 수 있는 구조
  경사 하강법 : 함수의 기울기로 최소값 탐색 알고리즘
구성요소 시입은출 원매매
  시간 – 순차적으로 연결된 시간의 흐름
  입력 – 해당 시간에 입력된 자극이나 입력 값
  은닉층 – 시간 경과 후 재사용 위해 저장한 배열 정보
  출력 – 이전 상태와 입력 값을 연산하여 나온 결과
구조 
  One to many / 일대다 - 이미지 캡셔닝, 라벨링 등 활용
  Many to one / 다대일 - 감성분류, 스팸메일 분류
  Many to Many / 다대다 구조 - 기계번역, 챗봇
장기의존성 / Vanishing Grandient Problem 문제
  1) RNN 은 하나의 네트워크가 여러 개 복사된 형태를 띄고 있고 각각의 네트워크는 다음단계로 정보를 넘겨줌
  2) 시간에 따라 학습이 진행됨에 따라 앞에서 인풋으로 받은 정보가 학습에 미치는 영향이 점검 감소하다가 결국 사라져 버림
  3) 은닉층이 깊어질수록 장기 의존성 문제에 의해 학습 효율이 떨어져 LSTM 으로 발전

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
