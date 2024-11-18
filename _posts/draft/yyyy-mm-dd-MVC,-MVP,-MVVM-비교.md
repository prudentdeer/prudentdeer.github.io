---
title: MVC, MVP, MVVM 비교
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
      I. MVC, MVP, MVVM 비교
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MVC, MVP, MVVM 비교의 정의
        </div>
        <div class="para-cntnt">
            관계 - 컨1 뷰N &lt;&gt; 프1 뷰1 &lt;&gt; 뷰모델N 뷰1
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MVC, MVP, MVVM 비교
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MVC, MVP, MVVM 비교의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MVC,-MVP,-MVVM-비교.png" alt="MVC, MVP, MVVM 비교">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MVC, MVP, MVVM 비교의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            장점 - 단순, 직관적 &lt;&gt; 분리되어 테스트용이 &lt;&gt; 뷰, 뮤델 의존성없음
  단점 - 복잡도 증가 &lt;&gt; 뷰, 프리젠터 1:1 의존성 &lt;&gt; 뷰와 모델 설계 어려움

MVC → 복잡도 완화 → MVP → 양방향통신 → MVVM

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
