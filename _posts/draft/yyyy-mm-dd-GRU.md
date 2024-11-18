---
title: GRU
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
      I. LSTM 경량화, GRU
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. GRU의 정의
        </div>
        <div class="para-cntnt">
            RNN 장기의존성 문제를 해결위해 Reset, Update gate 이용한 LSTM의 경량화 유닛
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. GRU
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. GRU의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/GRU.png" alt="GRU">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. GRU의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 리업캔히
  Reset Gate - 과거의 정보를 적당히 리셋
  Update Gate - 과거와 현재의 정보의최신화 비율을 결정
  Candidate - 현 시점의 정보 후보군을계산하는 단계
  Hidden Layer - update gate 결과와 candidate 결과를 결합
LSTM GRU 비교 (Gated Recurrent Unit)
  목적 - RNN 의 장기의존성 문제해결 &lt;&gt; LSTM 경량화
  구조 - 3개의 게이트 &lt;&gt; 2개의 게이트 (Update gate, Reset gate)
  특징 - 충분한 데이터 있으면 성능우수 &lt;&gt; 학습시간 짧음, 적은데이터 학습가능

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
