---
title: DGPS
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
      I. 기준국에서 오차정보를 생성하여, 방송하는 DGPS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DGPS의 정의
        </div>
        <div class="para-cntnt">
            기존 GPS가 갖는 위성의 위치에 따른 오차를 보정하여 정확도를 높이기 위한 오차보정 측위기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DGPS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DGPS의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DGPS.png" alt="DGPS">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DGPS의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  기지국 - GPS 위성에서 수신되는 신호의 오차 계산
  수신기 - Rover, 기지국 오차정보 이용해 GPS 측정값을 보정
오차유형
  대기 중 신호지연 - 대기를 통과하면서 속도가 느려지거나 빨라지는 대기 중의 신호 지연
  위성 시계오차 - GPS 위성의 원자 시계 오차 고려하여 보정
  전리층 오차 - 대기 중의 전자에 의해 위성 신호가 지연되거나 앞서는 현상
장점
  정확도 향상 - DGPS는 기지국과 수신기 간의 협력을 통해 정확도 향상
  저렴한 비용 - DGPS 시스템은 상대적으로 저렴하게 구축
단점
  지역제한 - DGPS는 기지국과 수신기 사이의 거리에 따라 정확도가 감소
  유지관리 필요 - 기지국의 설치와 유지 보수가 필요

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
