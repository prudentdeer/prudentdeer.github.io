---
title: GNN
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 인공지능]
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
      I. 그래프구조 딥러닝, GNN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. GNN의 정의
        </div>
        <div class="para-cntnt">
            데이터 특징추출 위해 이웃 노드간 특징 벡터를 찾아내는 그래프 기반 신경망 모델
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. GNN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. GNN의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/GNN.png" alt="GNN">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. GNN의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          프로세스
  변환 – Non-Euclidean 공간에 존재하는 복잡한 형태의 데이터를 신경망 학습에 적합한 형태로 변환
    인접 행렬 
    노드특성 행렬       
  취합 – 각 레이어에서 타겟 노드에 인접한 모든 이웃 노드의 은닉 변수 정보를 취합
    Target Node
    Hidden State
  결합 – 타겟 노드와 앞서 결합된 이웃 노드의 은닉 변수 정보 기반 타겟 노드 업데이트
    Hidden State
    Aggregated Information     
  생성 - 모든 노드의 은닉변수를 결합하여 그래프 단위 은닉변수 생성
    Regression
    Classification 
  출력 - 특정 레이어까지 과정 반복 후 노드 별 임베딩 계산하여 출력
    Node, Edge, Graph
    Graph, Embedding

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
