---
title: 메타학습
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
      I. 학습법을 학습하는, 메타학습
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 메타학습의 정의
        </div>
        <div class="para-cntnt">
            적은 양의 데이터와 주어진 환경만으로 스스로 학습하고, 새로운 문제에 적응하는 학습방식
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 메타학습
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 메타학습의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/메타학습.png" alt="메타학습">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 메타학습의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 메그확온 제원퓨
  메트릭기반 / 유사도 - 데이터 간 유사도를 측정하는 '메트릭(metric)'을 학습
  그래디언트기반 / 알고리즘 - 학습 알고리즘을 학습위해 그래디언트 알고리즘의 초깃값 학습
  확률모델 / 태스크 - 태스크의 모호함을 해결하고자 파라미터 불확실성을 다루는 능력
  온라인 / 순차적 - 실제 상황을 고려해 시간에 따라 순차적으로 학습이 진행 
학습종류
  Zero Shot / K = 0 - 한번도 관측되지 않은 클래스학습
  One Shot / K = 1 - 하나의 샘플만 주어지는 학습
  Few Shot / K &gt; 1 - 클래스별 소수 샘플로 학습
Zero-shot, One-shot, Few-shot 비교
  개념 - 샘플 X &lt;&gt; 하나의 샘플 &lt;&gt; 몇개의 샘플
  목표 - 일반화 &lt;&gt; 단일 예에서 일반화 &lt;&gt; 작은예제에서 일반화

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
