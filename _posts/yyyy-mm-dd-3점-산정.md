---
title: 3점 산정
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 프로젝트관리]
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
      I. PERT, 3점 산정기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 3점 산정의 정의
        </div>
        <div class="para-cntnt">
            프로젝트 일정산정을 위해 낙관치O, 비관치P, 최빈치M 의 산정 값을 계산하여 산정하는 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 3점 산정
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 3점 산정의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/3점-산정.png" alt="3점 산정">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 3점 산정의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  불확실성 고려, 평균화
구성요소
  추정치 - 요소 낙관치 (O) / 최빈치 (Most likely) / 비관치 (P)
  계산식 종류 삼베
    삼각분포 - (tO + tM + tP) / 3
    베타분포 - (tO + 4tM + tP) / 6
    표준편차 - sigma (p - o) / 6
    1~3 sigma - 신뢰도 68%, 95%, 99%
    분산 - ((비관치 – 낙관치) / 6) ^ 2

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
