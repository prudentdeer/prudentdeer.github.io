---
title: 딥페이크
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
      I. 진짜 같은 가짜 동영상, 딥페이크
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 딥페이크의 정의
        </div>
        <div class="para-cntnt">
            GAN 이용해 기존 영상에 다른 영상이나 이미지 정보를 합성하여 콘텐츠를 생성하는 합성기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 딥페이크
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 딥페이크의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/딥페이크.png" alt="딥페이크">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 딥페이크의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          주요기술
  데이터
    수집 &amp; 훈련 - Source Video와 Target Video 이미지 및 영상정보 수집
    프레임 적용 &amp; 합성 - 프레임 단위로 적용 후 LSTM 네트워크를 활용
  알고리즘
    GAN - 동영상의 모션 패턴을 모델링하거나 이미지에서 물체의 3D 모델을 재구성 처리
    LSTM - CNN과 LSTM 기반의 RNN을 이용하여 벡터화 처리

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
