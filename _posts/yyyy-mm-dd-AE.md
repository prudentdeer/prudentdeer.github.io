---
title: AE
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
      I. 압축과 재구성, 오토인코더
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. AE의 정의
        </div>
        <div class="para-cntnt">
            차원축소를 위해  입력, 출력 크기 동일한 Latent Feature 구하는 비지도학습 알고리즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. AE
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. AE의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/AE.png" alt="AE">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. AE의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 인디라매 스파디배
  구성요소
    Encoder - 입력데이터 저차원 표현 압축
    Decoder - 압축검증, 복구, 입력 동일크기 출력데이터 생성
    Latent Variable - 잠재적인 벡터 형태의 변수
    Manifold Learning - 고차원 &gt; 저차원 매핑, 차원축소
  유형
    Stacked AE - AE에서 hidden layer의 개수를 늘린것
    Sparse AE - AE에서 Hidden layer 내의 Node 수를 늘린것
    Denoising AE - 입력층에서 Hidden layer로 갈 때, 고의적 Noise를 추가한 것 (고성능)
    Variational AE - 유사하지만 새로운 데이터를 생성
오토인코더와 VAE 비교
  목적 - 동일한 이미지 출력 &lt;&gt; 비슷한 데이터 생성
  잠재벡터 - 고정 &lt;&gt; 확률적
  학습 - 잠재공간 포인트 &lt;&gt; 잠재공간 정규분포
- 비지도학습이지만 과적합이 발생할 수 있음
https://velog.io/@jochedda/%EB%94%A5%EB%9F%AC%EB%8B%9D-Autoencoder-%EA%B0%9C%EB%85%90-%EB%B0%8F-%EC%A2%85%EB%A5%98

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
