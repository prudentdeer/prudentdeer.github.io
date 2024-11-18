---
title: 식별, 비식별관계
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 데이터베이스]
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
      I. 식별관계, 비식별관계 비교
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 식별, 비식별관계의 정의
        </div>
        <div class="para-cntnt">
            식별관계 - 상위 엔티티의 주식별자를 하위 엔티티로 상속할 때, 주 식별자에 포함시키는 관계
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 식별, 비식별관계
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 식별, 비식별관계의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/식별,-비식별관계.png" alt="식별, 비식별관계">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 식별, 비식별관계의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            비식별관계 - 상위 엔티티의 주식별자가 하위 엔티티로 상속될 때, 일반 속성에 포함되는 관계
상세비교
  목적 - 강한 연결관계 &lt;&gt; 약한 연결관계
  자식 - 자식 주식별자 구성에 포함 &lt;&gt; 자식 일반속성에 포함
  표기법 - 실선 &lt;&gt; 점선

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
