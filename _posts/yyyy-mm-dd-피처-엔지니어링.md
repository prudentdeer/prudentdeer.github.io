---
title: 피처 엔지니어링
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
      I. 피처 엔지니어링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 피처 엔지니어링의 정의
        </div>
        <div class="para-cntnt">
            모델의 성능향상을 위해 데이터에서 분석에 사용할 피처를 추출, 선택, 개선, 변환하는 프로세스
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 피처 엔지니어링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 피처 엔지니어링의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/피처-엔지니어링.png" alt="피처 엔지니어링">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 피처 엔지니어링의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          기법 수범 결이비레원
  수치형
    결측값 처리 - 데이터가 없는 값을 평균/중앙/최빈 값으로 채우는 기법
    이상값 처리 - 존재할 수 없는 값 혹은 범위를 벗어나는 값을 찾아 처리 기법
    비닝 (binning) - 데이터를 n개의 빈(bin)으로 나누어 담는 기법
  범주형
    레이블인코딩 - 문자열 데이터를 수치로 표현하여 변경하는 기법
    원-핫 인코딩 - 레이블 인코딩의 숫자 크기 문제를 해결하기 위해 더미(dummy) 변수화 하여 처리하는 기법

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
