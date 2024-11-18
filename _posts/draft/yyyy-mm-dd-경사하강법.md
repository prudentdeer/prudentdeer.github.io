---
title: 경사하강법
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
      I. 신경망의 연결 가중치 최적화를 위한 경사하강법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 경사하강법의 정의
        </div>
        <div class="para-cntnt">
            손실함수 최소값 찾기위해 미분을 통해 이동하며 기울기 계산하는 가중치이동 알고리즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 경사하강법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 경사하강법의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/경사하강법.png" alt="경사하강법">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 경사하강법의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          경사하강법의 유형 배미확
  배치 / 모든데이터 - 모든데이터 학습, 오차이용 가중치 갱신 계산, 가중치 한번에 계산
  미니배치 / 배치크기 - 훈련데이터에서 소량 데이터를 적당히 선택해 학습 후 갱신처리
  확률적 / 샘플데이터 - 샘플 데이터셋에 대해서만 경사를 계산후 신경망 가중치 조절
경사하강법 문제점
  Overshooting -학습률 클 경우 문제발생
  Local Minimum - 학습률 작을경우 문제발생

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
