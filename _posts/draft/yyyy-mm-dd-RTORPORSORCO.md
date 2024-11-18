---
title: RTORPORSORCO
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 경영전략]
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
      I. DR 및 BCP의 핵심 구성 요소, RTO, RPO
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. RTORPORSORCO의 정의
        </div>
        <div class="para-cntnt">
            업무중단 시점으로부터 복구되어 업무가 정상적으로 가능할 때까지의 목표시간 (복구목표시간)
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. RTORPORSORCO
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. RTORPORSORCO의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/RTORPORSORCO.png" alt="RTORPORSORCO">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. RTORPORSORCO의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          RPO - Recovery Point Objectives
  업무중단 시점으로부터 데이터 복구가 수행되어야 하는 목표시점 (복구목표지점)
RCO - Recovery Communication OBjectives
  네트워크복구시간목표
RSO - Recovery Scope Objectives
RTO 와 RPO 에 따른 DR 결정방법
  Mirror Site    RTO = 0              WAS, 높은 비용
  Hot Site         RTO &lt;= 2H        데이터 실시간 미러링
  Warm Site    RTO &lt;=  1W       중요성이 높은 정보기술 자원
  Cold Site       RTO &gt;= 수개월   데이터만 원격지 보관

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
