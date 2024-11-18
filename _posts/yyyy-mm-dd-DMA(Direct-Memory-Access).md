---
title: DMA(Direct Memory Access)
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
      I. CPU 성능개선 위해, CPU 개입없이 주기억장치와 I/O 장치간 데이터 직접 전송하는 엑세스기술
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DMA(Direct Memory Access)의 정의
        </div>
        <div class="para-cntnt">
          '전버싸디 연단분통입
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DMA(Direct Memory Access)
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DMA(Direct Memory Access)의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DMA(Direct-Memory-Access).png" alt="DMA(Direct Memory Access)">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DMA(Direct Memory Access)의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          
[정의] CPU를 통하지 않고 주변장치(I/O 장치)와 주기억장치 사이의 데이터 전송을 담당하는 장치
[동작모드-전송] 1) Burst Mode 2) Cycle Stealing 3) Interleaved DMA
                   4) Demand Transfer Mode
[동작모드-연결] 1) 단일버스분리식, 2) 단일버스통합형, 3) 입출력버스

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
