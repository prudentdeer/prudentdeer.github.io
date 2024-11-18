---
title: 교차검증
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
      I. 학습모델 신뢰성 향상, 교차검증
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 교차검증의 정의
        </div>
        <div class="para-cntnt">
            데이터부족 극복위해 Training Set, Validation Set 분할하는 모델정확도 검증기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 교차검증
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 교차검증의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/교차검증.png" alt="교차검증">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 교차검증의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형
  소모적 LLR KHB
    LOOCV - N-1개의 학습 데이터셋과 1개의 검증 데이터셋
    LpOCV - N-p개의 학습 데이터셋과 p개의 검증 데이터셋
    Random
  비소모적
    K-Fold - K개의 Fold 학습, 검증 후 평균
    Hold out - 전체를 학습, 검증데이터로 분리
    Bootstrap
소모, 비소모적 교차검증 비교
  추출 - Random &lt;&gt; 지정
  속도 - 상대적 느림 &lt;&gt; 상대적 빠름
  정확도 - 상대적 정확 &lt;&gt; 상대적 부정확
- 데이터부족시 특성은 유지한채 많은 데이터 확보방법
https://losskatsu.github.io/machine-learning/cross-validation/#%EC%B0%B8%EA%B3%A0%EB%A7%81%ED%81%AC

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
