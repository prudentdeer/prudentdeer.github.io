---
title: 재사용 (Reuse)
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
      I. 표준화를 통한 개발 생산성 향상, 재사용
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 재사용 (Reuse)의 정의
        </div>
        <div class="para-cntnt">
            개발 생산성을 높이기 위하여 반복적으로 사용하기 적합하도록 표준화하여 구성하는 방법 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 재사용 (Reuse)
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 재사용 (Reuse)의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/재사용-(Reuse).png" alt="재사용 (Reuse)">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 재사용 (Reuse)의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          주요기법 카프리 폭크 CPLi POGC
  Copy - 소스코드의 copy, 목적에 맞게 재사용
  Pre-processing - Include 함수를 사용하여 compile 시에 포함되도록 하는 방법
  Library - Sub program 집합인 Library를 활용하여 Link에 포함
  Package - 전역변수, Package Interface 를 통한 정적인 활용방법
  Object - 전역변수, Object Interface를 통한 동적인 활용방법
  Generics - Object의 다형성 이용
  Component - 컴포넌트의 독립성, 조립성, 표준성 등을 활용 

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
