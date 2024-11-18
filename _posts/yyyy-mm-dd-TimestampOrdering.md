---
title: TimestampOrdering
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
      I. 트랜젝션 순서지정 방식, Timestamp Ordering
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. TimestampOrdering의 정의
        </div>
        <div class="para-cntnt">
            트랜잭션을 타임스탬프, 스케쥴러를 이용해 직렬화하여 순서를 보장하는 동시성제어기법 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. TimestampOrdering
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. TimestampOrdering의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/TimestampOrdering.png" alt="TimestampOrdering">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. TimestampOrdering의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  직렬성 보장 - 상충되는 연산들이 타임 스탬프 순서로 처리됨으로 직렬성 (Serializability)이 보장
  교착상태 방지 - 트랜잭션이 결코 기다리는 경우가 없으므로 교착상태 (Deadlock) 를 방지
  연쇄복귀 초래 - 문제점은 연쇄복귀 (Cascading Rollback) 를 초래
구성요소 논시RW
  생성방법
    논리적 계수 - 계수를 하나씩 증가시켜 트랜잭션의 타임스탬프 값으로 부여
    시스템 시계 - 시스템 시계의 값을 그 트랜잭션의 타임스탬프 값으로 부여
  운영방식
    read_TS(x) - x에 대한 읽기 작업이 최종적으로 성공한 시간
    write_TS(x) - x에 대한 쓰기 작업이 최종적으로 성공한 시간

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
