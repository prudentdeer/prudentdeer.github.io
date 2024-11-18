---
title: ROC 커브
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
      I. ROC 커브
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ROC 커브의 정의
        </div>
        <div class="para-cntnt">
            모든 분류 임계값에서 모델성능 평가하기위한 FPR 과 TPR 기반의 곡선그래프
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. ROC 커브
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ROC 커브의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/ROC-커브.png" alt="ROC 커브">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. ROC 커브의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 거참
  X축 FPR (1 - 특이도) - 아닌데 맞다고한거, 실제값이 False 인 관측치 중 예측치가 적중한 정도 
  Y축 TPR (민감도) - 맞는데 맞다고한거, 실제값이 True 인 관측치 중 예측치가 적중한 정도

TPR (True Positive Rate): 1인 케이스에 대해 1로 바르게 예측하는 비율 (Sensitivity), 암 환자에 대해 암이라고 진단
FPR (False positive rate): 0인 케이스에 대해 1로 틀리게 예측하는 비율 (1-Specificity), 정상에 대해 암이라고 진단

https://angeloyeo.github.io/2020/08/05/ROC.html

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
