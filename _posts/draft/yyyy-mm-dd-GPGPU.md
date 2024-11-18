---
title: GPGPU
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
      I. GPU 의 수행능력 확대, GPGPU
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. GPGPU의 정의
        </div>
        <div class="para-cntnt">
            GPU의 그래픽 처리뿐 아니라 CUDA, OpenCL 이용해  CPU가 처리하던 연산 처리 프로세서
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. GPGPU
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. GPGPU의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/GPGPU.png" alt="GPGPU">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. GPGPU의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 쿠오 심피 캐그
  API
    CUDA - GPU 알고리즘 작성할 수 있도록 하는 기술
    OpenCL - 개방형 범용 병렬 컴퓨팅 프레임워크
  핵심요소
    SIMD 코어 - 병렬 연산 처리를 위한 스레드 프로세서들 집합
    PCI 연동부 - CPU와 통신하거나 CPU측 메모리 접근위한 버스
  메모리
    캐시 메모리 - 코어 내/외부 공유메모리와 메모리와의 정합수행
    그래픽 메모리 - GPU에서 사용하는 고속의 메모리
GPGPU 활용위한 HSA (Heterogeneous System Architecture)
  개념 - CPU와 GPU를 하나의 연산체로 간주하는 추상계층을 생성하는 이기종 아키텍처
  HQ - 커널모드 생략, 사용자모드작업 gpu 부여 (Heterogeneous Queuing)
  HUMA - CPU와 GPU 메모리 공유 (Heterogeneous Unified Memory Architecture)

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
