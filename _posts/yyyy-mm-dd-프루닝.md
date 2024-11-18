---
title: 프루닝
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
      I. 모델의 경량화, 프루닝
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 프루닝의 정의
        </div>
        <div class="para-cntnt">
            딥러닝 모델 경량화를 위해 학습 후 가중치가 낮은 노드, 연결을 삭제하는 경량화 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 프루닝
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 프루닝의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/프루닝.png" alt="프루닝">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 프루닝의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 가규활 스글로
  가중치기반
    Weight Pruning - 작은 가중치 값 제거
    Magnitude Pruning - 가중치의 절대값이 작은 가중치를 제거
    Activation Pruning - 영향이 작은 뉴런을 제거
  구조기반
    Structured Pruning - 특정 구조적 패턴에 따라 가중치나 뉴런을 제거
    Global Pruning - 일정 비율의 가중치를 제거
    Local Pruning - 각 층 또는 부분 가중치 또는 뉴런을 제거하는 방법
프루닝, 드랍아웃 비교
  개념 - 뉴런 제거 &lt;&gt; 뉴런 비활성화
  목적 - 경량화 &lt;&gt; 오버피팅 방지, 일반화 능력 향상
  시점 - 학습 후 &lt;&gt; 학습 중
  수행 - 작은 가중치 삭제 &lt;&gt; 랜덤 뉴런 비활성

pruning : 파라미터 재사용 X
dropout : 파라미터 재사용 O

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
