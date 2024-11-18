---
title: CNN
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
      I. 합성곱 신경망, CNN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CNN의 정의
        </div>
        <div class="para-cntnt">
            이미지 인식, 분류위해 Convolution, Pooling 통해 피처추출, 차원축소 신경망 알고리즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. CNN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CNN의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/CNN.png" alt="CNN">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. CNN의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          기술요소 컨폴풀소 빅드렐
  레이어 구성
    Convolution 레이어 - 컨볼루션 연상을 통해 특징을 추출
    Pooling 레이어 - 차원축소, 컨볼루션 층에서 출력된 특징 지도를 압축하여 특정 데이터를 강조
    Fully Connected 레이어 - 이전 레이어 모든 결과 하나로 연결
    Softmax
  성능개선
    BigData - 다양한 데이터 학습으로 오버피팅 해결
    드랍아웃 - 일부 레이어 제거로 오버피팅 해결
    ReLU - 기울기 소실문제 해결 (Rectified Linear Unit)
CNN, RNN, DNN 비교
  구조 - 합성곱신경망 &lt;&gt; 순환신경망 &lt;&gt; 심층신경망
  데이터 - 이미지, 비전 &lt;&gt; 시퀀스 데이터 &lt;&gt; 다양한 데이터
  활용분야 - 이미지 분류 &lt;&gt; 자연어 처리 &lt;&gt; 입력값 추출
- CNN은 컴퓨터비전 분야의 핵심 알고리즘

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
