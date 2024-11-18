---
title: 파인튜닝
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
      I. 인공지능 품질향상 위한 파인튜닝
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 파인튜닝의 정의
        </div>
        <div class="para-cntnt">
            사전학습된 모델 매개변수를 세밀하게 조정하여 특정작업에 적합하도록 하는 튜닝기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 파인튜닝
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 파인튜닝의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/파인튜닝.png" alt="파인튜닝">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 파인튜닝의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 풀피리 전하가레
  유형
    Fully - 매개변수를 포함하여 모델 전체 파인튜닝
    Feature Extraction - 중간 레이어에서 추출된 특성을 사용 새로운 모델 훈련
    Repurposing - 일부 레이어만 파인튜닝
  기법
    전이학습 - 기존에 훈련된 모델을 가져와서 특정 작업에 맞게 조정하는 방법
    하이퍼 파라미터 - 학습률, 배치크기, 최적화 알고리즘 등을 미세 조정
    가중치 업데이트 - 새로운 데이터 셋에 대한 손실을 최소화 하도록 조정
    레이어 추가 - CNN 등 중간 Layer 추가로 새로운 작업의 특징 캡쳐
파인튜닝, 프롬프트엔지니어링 비교
  대상 - 모델 &lt;&gt; 입력값
  장점 - 도메인 최적화 &lt;&gt; 결과 품질향상
  단점 - 고비용 &lt;&gt; 모델의존적
- 일반화 성능은 저하될수 있으므로 주의 필요

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
