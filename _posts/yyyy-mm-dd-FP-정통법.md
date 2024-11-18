---
title: FP 정통법
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 소프트웨어공학]
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
      I. 분석, 설계이후의 측정, 정통법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. FP 정통법의 정의
        </div>
        <div class="para-cntnt">
            분석/설계 이후 정확도, 객관적 측정위해 기능별 복잡도 계산통한 기능점수 산정기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. FP 정통법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. FP 정통법의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/FP-정통법.png" alt="FP 정통법">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. FP 정통법의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          측정항목 데레데참
  데이터 기능 - DET, RET / 데이터요소 유형, 레코드요소 유형 
  트랜젝션 기능 - DET, FTR / 데이터요소 유형, 참조하는 ILF 또는 EIF의 수
측정시점
  분석, 설계 이후 측정 - 정확도 향상, 객관성 확보
간이법 정통법 비교 
  목적 - 개략적인 견적 산정 &lt;&gt; 상세 기능점수 측정
  측정 - ILF, EIF, EI, EO, EQ &lt;&gt; DET, RET, FTR
  복잡도 - 평균복잡도 &lt;&gt; 기능별 복잡도
  적용시기 - SW개발 전 단계 &lt;&gt; 설계 단계 이후
  장점 - 습득과 적용이 용이 &lt;&gt; 간이법 대비 정확도가 높음
  단점 - 정통법 대비 정확도가 낮음 &lt;&gt; 습득과 적용이 어려움

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
