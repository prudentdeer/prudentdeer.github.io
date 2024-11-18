---
title: 고릴라테스트
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
      I. 고릴라테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 고릴라테스트의 정의
        </div>
        <div class="para-cntnt">
            특정 모듈이나 기능에 집중하여 심층적인 평가를 통해 잠재적인 버그를 찾는 테스트
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 고릴라테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 고릴라테스트의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/고릴라테스트.png" alt="고릴라테스트">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 고릴라테스트의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          몽키와 고릴라테스트 비교
  입력 - 무작위 테스트 &lt;&gt; 특정 모듈이나 기능에 집중 
  목적 - 안정성, 버그확인 &lt;&gt; 모듈버그확인 
  대상 - 전체 시스템 &lt;&gt; 모듈
  기법 - Fuzz, 랜덤 &lt;&gt; Fault tolerance/Frustrating
  장점 - 새로운 버그발견 &lt;&gt; 신뢰성 확보
  단점 - 버그재현불가, 낮은 정확도 &lt;&gt; 비정상 시나리오 간과 

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
