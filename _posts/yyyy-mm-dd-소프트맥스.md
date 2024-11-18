---
title: 소프트맥스
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
      I. 소프트맥스
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 소프트맥스의 정의
        </div>
        <div class="para-cntnt">
            뉴런의 출력값에 대하여 class 분류위해 마지막 단계에서 출력값에 대한 정규화를 해주는 함수
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 소프트맥스
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 소프트맥스의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/소프트맥스.png" alt="소프트맥스">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 소프트맥스의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  출력값 - 0에서 1.0 사이의 실수
  출력의 총합 - 1
원핫 인코딩과 소프트맥스 비교
  출력형태 - 이진벡터 &lt;&gt; 확률분포 벡터
  출력값해석 - 단일 클래스 확률1, 나머지는 0 &lt;&gt; 모든 클래스 합이 1
  사용예시 - 이미지 분류, 텍스트 분류 &lt;&gt; 다중 클래스 분류
- 소프트맥스, 원핫 인코딩 오차를 계산하기 위해서 손실함수로 cross-entropy 함수를 사용

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
