---
title: NoSQLBASE 속성
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
      I. NoSQL의 BASE 속성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NoSQLBASE 속성의 정의
        </div>
        <div class="para-cntnt">
            ACID와 반대로 가용성과 성능을 중시하는 특성을 가진 분산 시스템의 NoSQL의 특성
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. NoSQLBASE 속성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NoSQLBASE 속성의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/NoSQLBASE-속성.png" alt="NoSQLBASE 속성">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. NoSQLBASE 속성의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          BASE 설명
  Basically Available / 접근성 - 언제든지 데이터는 접근할 수 있어야 하는 속성
  Soft-State / 일관성 X - 특정 시점에서는 데이터의 일관성이 보장되지 않는 속성
  Eventually Consistency / 일관성 O - 최종적으로 데이터의 일관성이 유지되는 속성
ACID 와 BASE 의 비교
  적용분야 - RDBMS &lt;&gt; NoSQL
  범위 - 트랜젝션 한정 &lt;&gt; 시스템 전체
  중점 - Commit 집중 &lt;&gt; 가용성
  시스템 - 엄격한관리 &lt;&gt; 성능에 초점
  효율성 - 테이블 디자인 &lt;&gt; 쿼리 디자인

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
