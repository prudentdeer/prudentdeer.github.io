---
title: 무결성, 정합성 차이
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
      I. 데이터 무결성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 무결성, 정합성 차이의 정의
        </div>
        <div class="para-cntnt">
          데이터 정합성
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 무결성, 정합성 차이
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 무결성, 정합성 차이의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/무결성,-정합성-차이.png" alt="무결성, 정합성 차이">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 무결성, 정합성 차이의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            데이터의 올바른 유무와 상관없이 데이터들의 값이 서로 일치
무결성 정합성 비교
  중점 - 무효갱신으로부터 데이터 보호 &lt;&gt; 데이터의 모순성 제거
  목표 - 데이터의 완전한 일치 &lt;&gt; 모순성이 없는 데이터
  속성 - 데이터의 완전성 &lt;&gt; 데이터의 일치성
  범위 - 더 넓은 범위를 포함 &lt;&gt; 더 좁은 범위의 개념
  오류 - 인스턴스 중복 및 NULL 값 &lt;&gt; 비정규형을 사용
  종류 - 개체, 참조, 속성 무결성 &lt;&gt; 데이터의 선후행 관계 파악

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
