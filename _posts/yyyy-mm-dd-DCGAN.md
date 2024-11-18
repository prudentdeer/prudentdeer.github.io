---
title: DCGAN
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
      I. Mode Collapse 개선, DCGAN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DCGAN의 정의
        </div>
        <div class="para-cntnt">
            GAN의 Mode collapse 문제점 개선위해 Convolution layer 적용한 적대 신경망
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DCGAN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DCGAN의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DCGAN.png" alt="DCGAN">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DCGAN의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 생판구성
  생성자
    Relu, Tanh - Relu 함수 사용시 마지막 결과에서만 Tanh
  판별자
    Leaky Relu, Batch Normalization - 판별자 활성화 함수, 모든 레이어에 사용
  구조변화
    CNN - Fully-connected hidden layers 삭제
  성능개선
    High Resolution Image - 한번에 high resolution image를 generate 가능
GAN 활용사례 싸디스트
  Cycle GAN / 회화, 이미지 변환기술 - 인공지능 자율학습, 변환 기술
  Disco GAN / 이미지, 텍스트 매핑 - 자율적 객체간 특성파악, 양자 관계 파악기술
  Star GAN / 여러 도메인 동시변환 기술 - 도메인간 이미지 변환 특화 형태
  Stack GAN / 통번역 알고리즘 - 입력된 이미지를 문장과 단어로 해석
CGAN - 생성자와 판별자가 훈련하는 동안 추가 정보를 사용해 조건이 붙는 생성적 적대 신경망
InfoGAN - 데이터의 특징을 뽑아내고 이를 이용하여 더 의미 있는 특징을 생성하는 적대 신경망

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
