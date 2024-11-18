---
title: MDD
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
      I. MDA 기반의 SW 개발 방식, MDD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MDD의 정의
        </div>
        <div class="para-cntnt">
            소프트웨어 개발을 위해 도메인, 업무설계 모델을 사용하여 코드생성을 자동화하는 설계기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MDD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MDD의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MDD.png" alt="MDD">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MDD의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구현모델 (모델, 기능) 씨독종코
  CIM / 도메인 모델 - 업무분석가들이 만드는 비즈니스 도메인 모델
  PIM / 업무설계 모델 - 설계자들이 논리적으로 만드는 업무설계 모델
  PSM / 상세화 모델 - 실제 구현기술 적합하도록 상세화
  Code / 소스코드 변환 - PSM을 통해 자동으로 추출되는 소스코드 
  자동화도구
MDD, DDD 비교
  목표 - 모델사용 방법론 &lt;&gt; 도메인중심 방법론
  언어 - UML, DSL &lt;&gt; 언어에 종속되지 않음
  코드생성 - 모델에서 자동생성 &lt;&gt; 모델과 코드 간의 매핑
  주요기술 - UML, QVT, 모델 변환, 코드 생성 도구 &lt;&gt; 도메인 주도 설계 도구, 도메인 주도 패턴

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
