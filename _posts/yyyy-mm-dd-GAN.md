---
title: GAN
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
      I. 경쟁을 통한 원본 복제기술, GAN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. GAN의 정의
        </div>
        <div class="para-cntnt">
            생성자와 판별자가 서로 경쟁하는 과정을 통해 학습하고 개선하는 대표적 적대 신경망
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. GAN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. GAN의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/GAN.png" alt="GAN">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. GAN의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  준지도 학습 - 지도학습(구별자) + 비지도학습(생성자)
  MinMax Problem - 최소화와 최대화 경쟁 기반 성능 향상
구성요소 생판학잠
  Generator 
    정확도 최소화 - 랜덤 노이즈 기반 유사 변환
    Latice - 노이즈 생성과 결합
  Discriminator
    정확도 최대화 - 입력 데이터 진위여부 판별
    시그모이드 - 참, 거짓 판단하는 함수
  학습데이터
    샘플 데이터 - 모사할 original 샘플 데이터
  잠재변수
    랜덤 노이즈, 벡터 - 모사 데이터 생성 벡터
문제점
  Mode collapse - 한번 진짜라고 여겨진 가짜가 있으면, 새로운 가짜를 만들지 않고 대량생산함
해결방안
  DC GAN - 모든 pooling layer를 convolutional layer로 교체

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
