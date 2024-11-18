---
title: PIM
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
      I. 차세대 반도체 메모리, PIM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. PIM의 정의
        </div>
        <div class="para-cntnt">
            메모리벽 해결위해, TSV, DMA 이용 프로세서와 메모리를 하나의 칩에 집적한 메모리
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. PIM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. PIM의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/PIM.png" alt="PIM">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. PIM의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            - 메모리 벽은 CPU-메모리 간 대역폭의 한계로 CPU가 제 성능을 발휘하지 못하는 한계
구성요소 티디핌버 메로컨유
  Logic DIE
    TSV - 실리콘 관통 전극 패키징 기술, Stack Layer 의 수천 연결 지원
    DMA - Physical, Logical Address 의 변환수행, 가상메모리 지원
    PIM Core - DDR 에 고속 Access 지원, Data Intensive Processing
    BUS - 유기적 Data 전송위한 System Bus
  3D-packaged DRAM
    Memory DIE - 3D 적층 기술기반으로 물리적인 DRAM 의 결합
    Logic DIE - PIM 구현을 위한 논리단위 처리
  Processor DIE 
    Memory Controller - Process in memory 처리를 위해 Unit 과의 연계 수행
    Unit - 연산 수행을 위한 전통적인 Uni
PIM, PNM 비교
  프로세서 - 하나의칩 &lt;&gt; 근접배치
  장점 - 저지연, 고성능 &lt;&gt; Locality
  단점 - 설계복잡 &lt;&gt;  물리적제약
  활용 - 빅데이터 처리 &lt;&gt; 모바일디바이스
- 폰 노이만 구조의 병목현상, 전력소모 해결

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
