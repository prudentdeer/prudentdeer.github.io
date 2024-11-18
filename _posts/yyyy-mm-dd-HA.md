---
title: HA
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 컴퓨터구조]
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
      I. 가용성 극대화, HA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. HA의 정의
        </div>
        <div class="para-cntnt">
            무중단시스템 구성위해 두대이상 시스템을 클러스터로 구성하고 장애발생시 Failover 하는 기술 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. HA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. HA의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/HA.png" alt="HA">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. HA의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성유형 핫뮤컨
  Hot Standby / A-S - 가동 시스템과 평상시 대기상태의 백업 시스템으로 구성
  Mutual Takeover / A-A - 각각의 고유 업무수행, 장애발생시 상대 시스템 Failover, 동시에 2개 업무수행
  Concurrent Access / 병렬 - 여러개의 시스템 병렬처리, 전체가 Active한 상태로 업무수행
HA 와 FTS 비교
  중단시간 - 10초 ~ 300초 &lt;&gt; 0초
  구축비용 - 시스템의 약 2배 &lt;&gt; 시스템의 약 20~30배
  운영환경 - 범용시스템 &lt;&gt; 전용시스템
  활용사례 - 기업 홈페이지 &lt;&gt; 금융거래 사이트, 온라인 쇼핑몰

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
