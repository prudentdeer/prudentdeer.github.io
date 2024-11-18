---
title: DAG
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 디지털서비스]
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
      I. 블록체인 3.0 세대를 이끌 기술, DAG
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DAG의 정의
        </div>
        <div class="para-cntnt">
            개별요소들이 특정한 방향을 향하고 있으며, 순환하지 않는 구조 방향성 비순환 그래프 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DAG
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DAG의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DAG.png" alt="DAG">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DAG의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          수학적측면 위도축폐
  위상정렬 - 정점의 순서를 구하는 것
  도달 가능성 - 도달 가능 정점들의 집합을 찾는 문제
  추이적 폐쇄 - 동일한 도달 가능성을 가지면서 가장 많은 간선을 가진 그래프
  추이적 축소 - 그래프의 간선을 제거하여 크기를 줄이는 개념
성능적측면 성수확파
  성능우수 - 블록 생성 없이 트랜잭션이 다른 트랜잭션을 검증
  수수료 없음 - 채굴자가 없기 때문에 기본적으로 수수료 또한 미발생
  확장성 확보 - 사용량이 많아질 수록 검증의 신뢰도와 속도는 증가
  파셜 오더링 - 연결된 트랜잭션끼리만 그 쓰여진 순서를 정의가능
  확정합의를 하기 위해서는 모두가 동일한 상태를 가지고 있어야 하는데, 동시다발적으로 진행
기존 블록체인과 DAG 비교
  데이터구조 - 연속된 블록체인 &lt;&gt; 비순차적, 블록 간 연결없음
  처리속도 - 일반적으로 낮음 &lt;&gt; 높은 처리량, 병렬처리 가능
  채굴중립성 - 일부 중앙화 &lt;&gt; 높은 중립성
  주요사용사례 - 비트, 이더 &lt;&gt; IoTA, 헤쉬그래프, 탱글 등
- DAG는 블록체인의 트릴레마를 극복 할 수 있다

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
