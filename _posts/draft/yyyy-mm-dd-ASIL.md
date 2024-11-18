---
title: ASIL
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 필수암기]
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
      I. ISO 26262의 차량안전성 등급, ASIL
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ASIL의 정의
        </div>
        <div class="para-cntnt">
            전기전자 장치안전 표준 (IEC 61508) 의 안전성 보전등급 (SIL) 을 자동차에 맞게 개선 적용한 차랑안전성 보전등급
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. ASIL
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ASIL의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/ASIL.png" alt="ASIL">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. ASIL의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          결정요소 SEC
  S / S1 ~ S3 - 심각도 (Potential severity) 
  E / E1 ~ E4 - 노출가능성 (Probability of exposure)
  C / C1 ~ C3 - 통제가능성 (Controllability)
등급
  ASIL-D - 1억시간 당 사고/고장 1회 이하, 단일부품 고장위험 99% 이상까지 대책설계
  ASIL-C - 천만시간 당 사고 1회 이하, 단일부품 고장위험 97% 이상까지 대책설계
  ASIL-B - 천만시간 당 사고 1회 이하, 단일부품 고장위험 90% 이상까지 대책설계
  ASIL-A - 기준없음
ASIPCE vs ASIL
  개념 - 성숙도 평가모델 &lt;&gt; 안전 등급
  목적 - 자동차 소프트웨어 수준 심사 &lt;&gt; 자동차 H/W 및 S/W 안전도 표준 등급 제공
  등급범위 - 0 ~ 5 Level &lt;&gt;  A ~ D Level
  관련표준 - ISO 15504, ISO 12207 &lt;&gt; ISO26262

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
