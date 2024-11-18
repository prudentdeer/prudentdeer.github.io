---
title: 기울기 소실기울기 폭주
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
      I. 기울기소실 문제
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 기울기 소실기울기 폭주의 정의
        </div>
        <div class="para-cntnt">
            심층신경망의 역전파 알고리즘을 이용, 학습시 기울기가 점차 작아지는 비정상 수렴 현상
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 기울기 소실기울기 폭주
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 기울기 소실기울기 폭주의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/기울기-소실기울기-폭주.png" alt="기울기 소실기울기 폭주">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 기울기 소실기울기 폭주의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          발생원인
  초기값 오류 - 초기 가중치 값 오류
  은닉측 시그모이드 함수 사용 - 잘못된 활성화 함수 사용
해결방안 롱디렐리
  학습측면
    LSTM - 메모리기억 장기의존성 문제 해결
    DBN - 파인튜닝 이전 사전학습
  활성함수
    ReLU - 미분값의 보존
    Leaky ReLU - 음의 값 활용

기울기폭주 문제
정의 (Gradient Exploding)
  심층신경망의 역전파 알고리즘을 이용한 학습시 기울기가 점차 커지는 비정상 발산 현상

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
