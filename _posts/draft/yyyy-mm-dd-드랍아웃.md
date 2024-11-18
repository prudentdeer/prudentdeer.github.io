---
title: 드랍아웃
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
      I. 오버피팅 예방, 드롭아웃
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 드랍아웃의 정의
        </div>
        <div class="para-cntnt">
            딥러닝의 오버피팅 문제예방 위해 학습 중 랜덤으로 노드일부를 비활성하는 최적화 학습기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 드랍아웃
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 드랍아웃의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/드랍아웃.png" alt="드랍아웃">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 드랍아웃의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          매커니즘 포드백평
  Forward Propagation - 각 레이어에서 뉴런의 가중치와 활성화 함수를 통해 출력 계산
  Dropout 적용 - Dropout 비율에 따라 무작위로 뉴런을 비활성화
  Backward Propagation - 신경망의 출력과 실제 레이블 간의 차이를 계산하여 오류를 측정
  모델평가 - 모든뉴런 활성화한 상태로 평가진행
프루닝, 드랍아웃 비교
  개념 - 뉴런 제거 &lt;&gt; 뉴런 비활성화
  목적 - 경량화 &lt;&gt; 오버피팅 방지, 일반화 능력 향상
  시점 - 학습 후 &lt;&gt; 학습 중
  수행 - 작은 가중치 삭제 &lt;&gt; 랜덤 뉴런 비활성

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
