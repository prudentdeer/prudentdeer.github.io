---
title: 파티셔닝
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
      I. 대용량 처리를 위한, 파티셔닝의 개념 테이블, 경량화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 파티셔닝의 정의
        </div>
        <div class="para-cntnt">
            DB 성능향상 위해 DB내 하나의 테이블을 작은 단위로 분할, 경량화하는 DB 관리기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 파티셔닝
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 파티셔닝의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/파티셔닝.png" alt="파티셔닝">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 파티셔닝의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          장점
  인덱스 크기 작아짐 &gt; 성능향상
분할방법 범리해결
  범위분할 - 일정한 범위로 분할
  리스트분할 - 값 리스트를 각 파티션 지정
  해시분할 - 파티션 키에 해시함수 적용
  결합분할 - 각 기법의 장점 결합, 파티션의 서브파티션 구성
샤딩과 파티셔닝 비교
  개념 - DB 분산 &lt;&gt; 테이블 분해
  관리 - Master Node 관리 &lt;&gt; 별도 Master node 없음
  샤드키 - Key 저장 &lt;&gt; 별도 Key 없음
  증설 - Scale out &lt;&gt; Scale up
  조인 - Join 불가 &lt;&gt; Join 가능

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
