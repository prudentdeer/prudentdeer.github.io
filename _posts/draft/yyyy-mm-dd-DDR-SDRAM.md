---
title: DDR SDRAM
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
      I. [정의] 내부 메모리 셀의 동작 주파수를 높이지 않고도 기존 SDR SDRAM 에 비해 두배 이상의 성능 향상을 위해 외부주파수의 Rising/Falling Edge 각각에 데이터 전송하는 주기억장치
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DDR SDRAM의 정의
        </div>
        <div class="para-cntnt">
          DDR3 : 집적도/속도: 최대 8Gb/ 2.1Gbps
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DDR SDRAM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DDR SDRAM의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DDR-SDRAM.png" alt="DDR SDRAM">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DDR SDRAM의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
           코어 아키텍처: 8bank/페이지크기(최소 1KB)
DDR4 : DDR4(Double Data Rate 4) SDRAM: DDR3보다 2배 높은 3.2Gbps 속도, 2배 density 향상, 공정/아키텍처 진화로 20% 전력 소비 감소한 JEDEC에서 표준화한 고속의 DRAM
DDR5 : LPDDR5(Low Power Double Data Rate 5), 삼성전자, 10 나노급. 2018년 5G 적용 목적 등.

(Double data rate synchronous dynamic random access memory)

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
