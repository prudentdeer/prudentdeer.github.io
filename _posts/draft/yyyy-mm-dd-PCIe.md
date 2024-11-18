---
title: PCIe
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
      I. 고속직렬통신, PCI Express
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. PCIe의 정의
        </div>
        <div class="para-cntnt">
            확장가능 다수레인으로 구성된 물리계층기반 고속 데이터전송 제공 점대 점 연결 프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. PCIe
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. PCIe의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/PCIe.png" alt="PCIe">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. PCIe의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          PCIe 4.0, PCIe 5.0 
  전송속도 - 16GT/s &lt;&gt; 32GT/s 
  대역폭 - 최대 64GB/s &lt;&gt; 최대 128GB/s
  전력관리 - 동적 전력 할당 &lt;&gt; 향상된 전력 관리
  핫플러그 - 네이티브 솔루션 &lt;&gt; 동기식 제거 지원 
PCIe Bifurcation
  PCIe에서 사용하는 Lane을 목적에 따라 여러 개의 논리적인 브랜치로 분리하는 기능
PCIe Switch
  PCIe Lane을 여러 장치에 분배하여 연결을 확장하고 장치 간 데이터 전송을 중개하는 장치

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
