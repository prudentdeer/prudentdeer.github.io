---
title: CXL
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
      I. 데이터 전송 길의 확장, CXL
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CXL의 정의
        </div>
        <div class="para-cntnt">
            PCIe 물리계층에 구축된 CPU, 메모리, 디바이스 간 저지연 고속 인터커넥트 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. CXL
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CXL의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/CXL.png" alt="CXL">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. CXL의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          프로토콜 아캐멤
  CXL.io / PCIe 기능 - 장치탐색, DMA등  PCIe와 유사한 기능을 제공 
  CXL.cache / 캐시일관성 - MESI 이용 캐시일관성 유지 비대칭형 프로토콜
  CXL.mem / 메모리접근 - 호스트 프로세서가 주변장치의 메모리를 로컬 메모리처럼 사용하도록 제공
디바이스유형 아캐 아캐멤 아메
  Type 1 - 호스트 CPU의 캐시 메모리와 coherent한 캐시를 가지는 유형 
    프로토콜 - CXL.io, CXL.cache 
    활용 - 자체 메모리가 없는 스마트 NIC와 호스트 간의 구성 
  Type 2 - 호스트와 fully coherent한 캐시, 호스트가 관리하는 장치 메모리를 가지는 유형
    프로토콜 - CXL.io, CXL.cache, CXL.memory 
    활용 - 주로 GPU나 FPGA와 같은 가속기를 활용한 고성능 컴퓨팅이 요구되는 구성 
  Type 3 - 호스트가 관리하는 메모리로 구성된 장치 유형
    프로토콜 - CXL.io, CXL.memory 
    활용 - 주로 호스트의 메모리 버퍼나 SCM과 연결된 구성 - 메모리 용량 및 메모리 대역폭 확장에 사용 

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
