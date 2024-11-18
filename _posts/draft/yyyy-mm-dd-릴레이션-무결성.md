---
title: 릴레이션 무결성
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
      I. 릴레이션 무결성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 릴레이션 무결성의 정의
        </div>
        <div class="para-cntnt">
            릴레이션 조작시 삽입, 삭제, 갱신 트랜잭션의 수행 전과 후 의미적 관계를 유지하는 특성
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 릴레이션 무결성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 릴레이션 무결성의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/릴레이션-무결성.png" alt="릴레이션 무결성">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 릴레이션 무결성의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 상과집튜 즉지
  상태 제약 - 특정 시점에 만족되어야 하는 정적 제약 
  과도 제약 - DB 변경 전, 후 모두 만족해야 하는 동적 제약 
  집합 제약 - 튜플 집합 전체에 관련되어 적용되는 제약 
  튜플 제약 - 처리되고 있는 튜플에만 적용되는 제약 
  즉시 제약 - 연산이 수행되는 즉시 적용되는 제약 
  지연 제약 - 트랜잭션이 완전히 수행된 후 적용되는 제약

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
