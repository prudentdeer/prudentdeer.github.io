---
title: Index
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
      I. DB Index
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Index의 정의
        </div>
        <div class="para-cntnt">
            검색 연산을 최적화하기 위해 탐색 키값과 데이터의 위치정보로 구성되어 있는 데이터 구조
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Index
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Index의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Index.png" alt="Index">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Index의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  성능향상, 독립성, 알고리즘, Trade-off
구성요소
  Leaf Block - 테이블의 각 레코드에 대한 인덱스 정보를 가지고 있는 Block
  Block Header - 인덱스 컬럼의 구간 값과 인덱스 바의 물리적인 위치 정보
  Branched Block - Leaf Block과 Root Block 중간에서 Block간 정보에 대한 다리 역할
  Block내 인덱스 바 - 각 인덱스 간에 구분을 해주는 인덱스 헤더가 있으며, 각 자신에 직접 연결된 하위 레벨 Block의 인덱스 컬럼의 구간 값
  Root Block - Tree의 최상위 레벨에 위치하며, CRUD시 제일먼저 접근
분류
  형태 - 트리 기반 인덱스 / 해쉬 기반 인덱스 / 비트맵 인덱스
  목적 - 함수기반 인덱스 / 조인 인덱스 / 도메인 인덱스
  구조 - 정적 인덱스 / 동적 인덱스

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
