---
title: 병렬처리와 병행처리
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 컴퓨터구조]
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
      I. 병렬처리  
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 병렬처리와 병행처리의 정의
        </div>
        <div class="para-cntnt">
          병행처리
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 병렬처리와 병행처리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 병렬처리와 병행처리의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/병렬처리와-병행처리.png" alt="병렬처리와 병행처리">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 병렬처리와 병행처리의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            단일코어 환경 작업을 빠르게 교차수행하여 작업들이 동시실행처럼 보이는 처리기술
병렬처리와 병행처리 비교
  개념 - 동시실행 &lt;&gt; 교차수행
  구현 - 다중 CPU &lt;&gt; 인터리빙, 문맥교환
  장점 - 처리성능 향상 &lt;&gt; I/O 작업 및 동시성 문제 해결
  실행방식 - 동시 독립적 &lt;&gt; 시간분할 전환
  H/W요구 - 다중코어 필요 &lt;&gt; 다중코어 불필요
  의존성관리 - 의존성 낮음 &lt;&gt; 의존성 관리 및 동기화 필요
  사례 - AI 학습, 그래픽 렌더링, 빅데이터 처리 &lt;&gt; 웹 서버, DBMS, 운영체제

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
