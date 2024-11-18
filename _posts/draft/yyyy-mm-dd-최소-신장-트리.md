---
title: 최소 신장 트리
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 자료구조]
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
      I. Minimum Spanning Tree, 최소 신장트리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 최소 신장 트리의 정의
        </div>
        <div class="para-cntnt">
             모든 정점을 포함하는 무방향성 그래프에서 간선 가중치합이 최소가 되는 신장트리
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 최소 신장 트리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 최소 신장 트리의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/최소-신장-트리.png" alt="최소 신장 트리">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 최소 신장 트리의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          알고리즘 프크솔
  프림 - 시작점에서 가까운 정점 선택하면서 MST 구성
  크루스칼 - 최소비용 간선을 차례로 대입하면서 MST 구성
  솔린 - 동시에 여러 개의 간선을 선택하여 MST 구성
활용사례
  도로건설 - 도시를 모두 연결하는 도로길이 최소화  
  통신 - 전화선 길이 최소화 케이블망 구축
  배관설비 - 최단거리로 모든 파이프 연결 길이 최소화
  네트워크 - 라우터 경로설정, 최적 라우팅경로 선택

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
