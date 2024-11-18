---
title: 어텐션 매커니즘
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
      I. 어텐션 매커니즘
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 어텐션 매커니즘의 정의
        </div>
        <div class="para-cntnt">
            seq2seq의 기울기소멸 해결위해 출력단어 예측시점마다 가중치 계산하여 정확도 보정 메커니즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 어텐션 매커니즘
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 어텐션 매커니즘의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/어텐션-매커니즘.png" alt="어텐션 매커니즘">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 어텐션 매커니즘의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형
  Dot-Product Attention - Query와 Key의 내적 사용
  Scaled Dot-Product Attention - 내적 값을 Key 벡터의 차원 수의 제곱근으로 나누어 스케일링
  Additive Attention - Query와 Key 결합 후, 학습 가능 가중치 행렬 적용
  Multi-Head Attention - 여러 독립적 어텐션을 병렬로 수행 후 결과 결합

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
