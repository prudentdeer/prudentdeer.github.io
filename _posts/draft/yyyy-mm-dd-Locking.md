---
title: Locking
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
      I. 상호배제 동시성 제어기법, Locking
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Locking의 정의
        </div>
        <div class="para-cntnt">
            트랜잭션이 사용하는 데이터에 대하여 상호 배제 기능을 제공하는 동시성제어기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Locking
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Locking의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Locking.png" alt="Locking">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Locking의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          종류 공전
  공유락 (Shared Lock) - 데이터 항목에 대하여 읽기 read 만 가능, 다른 트랜젝션 read 만
  전용락 (Exclusive Lock) - 데이터 항목에 대해서 읽기read 와 기록 write 가 모두 가능, 다른 트랜젝션 불가능
수준 스리틱
  Strict - 모든 독점 locking이 완료시까지 unlock하지 않음 (연쇄복귀 문제X, 교착상태발생) 
  Rigorous - 모든 locking이 완료시까지 unlock하지 않음 (더 제한적, 연쇄복귀 문제X, 교착상태발생) 
  Static - 트랜젝션 수행 전부터 읽기/쓰기 집합 미리 선언 모든 항목 lock (교착상태 미발생, 비현실적)

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
