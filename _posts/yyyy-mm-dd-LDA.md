---
title: LDA
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
      I. 선형 판별분석, LDA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. LDA의 정의
        </div>
        <div class="para-cntnt">
            클래스 분리를 최대화하는 축을 찾기 위해 클래스내 분산 최소화, 클래스간 분산 최대화 알고리즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. LDA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. LDA의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/LDA.png" alt="LDA">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. LDA의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          프로세스 데산고선
  데이터 표준화 / Standard Scaling - 표준집합에 대한 스케일링
  산포행렬생성 / 평균벡터 계산 - 클래스내 산포행렬(SW), 클래스간 산포행렬(SB) 구성
  고유벡터계산 / 고유값선택 - SW 의 역행렬과 SB 의 곱행렬의 값에 대해 고유벡터와 고윳값 도출
  선형변환 / 선형변환 - 선택한 k 개의 고유벡터로부터 n X k 차원의 선형번환

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
