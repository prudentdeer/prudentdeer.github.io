---
title: 행렬기반 필터링
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
      I. 잠재요인 활용, 행렬분해기반 협업적 필터링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 행렬기반 필터링의 정의
        </div>
        <div class="para-cntnt">
            사용자와 아이템 간의 상호작용을 행렬분해하여 잠재요인활용 추천수행 필터링기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 행렬기반 필터링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 행렬기반 필터링의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/행렬기반-필터링.png" alt="행렬기반 필터링">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 행렬기반 필터링의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          기술요소 특확대행
  분해
    특이값 분해 (SVD) - 선형 대수의 개념 기반, 행렬을 세 개의 부분 행렬로 분해
  최적화
    확률적 경사하강법 (SGD) - 행렬 P와 Q를 업데이트하면서 최적의 파라미터를 찾음
    대체최소 제곱법 (ALS) - 사용자 특성과 아이템 특성을 번갈아가면서 최적화
  예측
    행렬 완성기법 (Matrix Completion) - 행렬을 완성하여 누락된 값을 예측
- 행렬연산기반 대용량 처리와 콜드스타트 문제 해결
콘텐츠, 협업, 행렬 필터링 비교
  대상 - 컨텐츠 특징 &lt;&gt; 아이템 + 사용자 &lt;&gt; 아이템 + 사용자
  원리 - 유사도 측정 &lt;&gt; 유사도 측정 &lt;&gt; 행렬분해
  신규아이템 - 가능 &lt;&gt; 보통 &lt;&gt; 어려움
  문제점 - 필터버블 &lt;&gt; 콜드스타트 &lt;&gt; 연산복잡도
- 추천시스템 과의존시 확증편향, 정보편식문제 주의

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
