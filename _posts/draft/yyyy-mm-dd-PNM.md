---
title: PNM
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
      I. 차세대 반도체 메모리, PNM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. PNM의 정의
        </div>
        <div class="para-cntnt">
            메모리벽 해결위해, HI, CXL 이용 프로세서와 메모리를 인접위치에 구현한 메모리
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. PNM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. PNM의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/PNM.png" alt="PNM">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. PNM의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            - 메모리 벽은 CPU-메모리 간 대역폭의 한계로 CPU가 제 성능을 발휘하지 못하는 한계
기술요소 이삼티 인씨에메 
  칩 기술
    이종 집적화, HI - 메모리와 프로세스 단일칩 통합
    3D Stacking - 여러칩을 수직으로 적층 거리최소화
    TSV - 수직적층
  메모리 기술
    In-Memory Computing - 메모리내 데이터 처리 기술
    CXL - 메모리와 CPU/GPU 연결 인터페이스 표준, Compute Express Link
    Accelerator - 특정작업 및 알고리즘 가속기술
    MCA - 데이터 엑세스 최적화/속도향상, Memory-Centric Architectures
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