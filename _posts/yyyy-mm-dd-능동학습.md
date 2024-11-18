---
title: 능동학습
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
      I. Auto Labeling 기법, 능동 학습
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 능동학습의 정의
        </div>
        <div class="para-cntnt">
            데이터를 일부만 학습 시킨 후, 이를 활용해 나머지 데이터를 라벨링하는 오토 라벨링 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 능동학습
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 능동학습의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/능동학습.png" alt="능동학습">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 능동학습의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          프로세스 모선교평
  모델학습 / Labeled Data - 라벨링 된 데이터 일부만 학습
  데이터 선별 / 불분명성 - 현재 학습 모델 기준 불분명성 높은 데이터를 선별
  데이터 교정 / Oracle - 큐레이터, 어노테이터 통해 오차를 교정해 품질 개선
  모델 평가 / Precision, Accuracy - 정확도와 정밀도 측정해 모델 평가

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
