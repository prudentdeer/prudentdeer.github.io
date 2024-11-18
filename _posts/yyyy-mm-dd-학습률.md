---
title: 학습률
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
      I. 학습률
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 학습률의 정의
        </div>
        <div class="para-cntnt">
            경사하강법에서 Loss 줄이기 위해, 일정크기의 보폭(Step size)을 지정하는 하이퍼 파라미터
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 학습률
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 학습률의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/학습률.png" alt="학습률">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 학습률의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          문제점
  오버슈팅 - 경사하강시 학습률이 과도하게 큰 경우 최저점을 지나쳐 손실이 다시 증가하는 현상
  로컬 미니멈 - 경사하강시 학습률이 과도하게 작은 경우 Global minimum 아닌 Local minimum 찾는 현상
해결방안
  하이퍼파라미터 학조가드
    학습률조절 - 초기에는 큰 학습률로 빠르게 수렴하고, 점차 작은 학습률로 미세 조정
    조기종료 - 성능이 향상되지 않으면 학습을 중단하는 방법
    가중치감쇠 - 손실 함수에 가중치의 크기에 대한 페널티를 추가
    드롭아웃 - 무작위로 일부 뉴런을 비활성화
  옵티마이저 슴나담 아라담

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
