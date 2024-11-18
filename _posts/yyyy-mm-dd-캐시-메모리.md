---
title: 캐시 메모리
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
      I. 장치간의 속도차이 극복을 위한 Cache Memory
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 캐시 메모리의 정의
        </div>
        <div class="para-cntnt">
            CPU와 주기억장치 속도차이 따른 성능저하를 줄이기위해 사이에 설치하는 고속메모리
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 캐시 메모리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 캐시 메모리의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/캐시-메모리.png" alt="캐시 메모리">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 캐시 메모리의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징 지사일
  Locality - 블록단위 특정부분 집중적 메모리 참조
  Mapping - 주기억장치와 캐시메모리간의 메모리 매핑 적용
  Coherence - 병렬처리 시 Local Cache 와 공유메모리간 일관성 유지
교체알고리즘 FLLRO
  FIFO - 선입선출 방식, 캐시에 가장 오래된 적재되어진 블록을 교체하는 방식
  LRU - 가장 오랫동안 사용되지 않은 블록을 교체하는 방식 (Least Recently Used)
  LFU - 참조되었던 횟수가 가장 적은 블록을 교체하는 방식 (Least Frequently Used)
  Random - 교체 후보들 중 임의로 선택하여 교체하는 방식
  Optimal - 향후 참조 되지 않을 블록을 교체하는 방식
캐시일관성 필요환경
  멀티프로세서 구조 - 다수의 클라이언트(프로세서)가 존재하는 환경 
  로컬캐시 프로세서 - 각각의 프로세서가 로컬 캐시를 가지는 환경 
필요이유
  Write Back 불일치 - 캐시 갱신 후 주기억장치 갱신 구조로 인한 불일치 발생 
  I/O 불일치 - I/O 동작에 의해 주기억장치 내용 변경(캐시 메모리는 변경 X) 

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
