---
title: XAI
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
      I. 설명가능한 인공지능, XAI
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. XAI의 정의
        </div>
        <div class="para-cntnt">
            인공지능의 의사결정에 대한 이유를 사람이 이해할 수 있는 방식으로 제시하는 인공지능
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. XAI
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. XAI의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/XAI.png" alt="XAI">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. XAI의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          기법
  모델독립적 
    LIME - 예측을 선형회귀 모델과 같이 해석이 가능한 모델로 근사하여 설명, Local Interpretable ModelAgnostic Explanations
    SHAP - 게임 이론에서 고안된 섀플리 값 개념 차용하여 AI 모델의 예측 크레딧을 각 입력 특징에 분배, Shapley Additive Explanation
  모델특정적
    LRP - 심층 신경망의 각 층 간의 비선형 연결을 테일러 전개 통해 선형으로 근사하는 과정에서 기울기 활용, Layer-wise Relevance Propagation
    IG - 입력 공간의 특정 베이스라인에서부터 설명하고자 하는 입력까지의 경로의 기울기 적분, Integrated Gradients
문제점
  AI 시스템의 추론이 틀렸음에도 해당 추론이 옳다고 설명이 제공된 경우
  결정권자 실수 유발하고 사용자를 오도
해결방안
  책임강화 - AI 지원에 대한 사용자의 맹목적 기대를 경감시키고 의사결정권자의 책임을 강화
  재론적설명 - 추론 결과에 대한 불확실성이 측정되는 시스템에 적용가능

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
