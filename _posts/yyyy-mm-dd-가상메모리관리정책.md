---
title: 가상메모리관리정책
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
      I. 가상메모리 관리정책
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 가상메모리관리정책의 정의
        </div>
        <div class="para-cntnt">
            가상메모리의 할당과 배치, 호출과 교체 정책과 프로세스를 결정하는 매커니즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 가상메모리관리정책
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 가상메모리관리정책의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/가상메모리관리정책.png" alt="가상메모리관리정책">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 가상메모리관리정책의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          관리정책 할배호교
  할당정책 연불
    연속할당 - 고정할당, 가변할당 기법
    불연속할당 - 페이징, 세그멘테이션, Paged Segmentation
  배치정책 퍼넥배워
    First Fit - 가장 처음에 크기 충분한 공간에 할당 / 가장 간단하고 빠름
    Next Fit - 가장최근 배치 블록부터 검사, 크기충분한 다음 위치 / 순차적 최적 배치
    Best Fit - 처음부터 끝까지 탐색후 가장 근접공간 할당 / 스캔시간, 최적공간 할당
    Worst Fit - 가장 큰 공간에 할당 / 비효율적, 분할구간 생김
  호출정책 예요
    요구호출 - 실행프로그램 요구시 참조페이지나 세그먼트만 주기억장치로 적재
    예상호출 - 참조될 것을 미리 예상하여 미리 주기억장치로 적재
  교체정책 FLLO
    FIFO - 가장 먼저 주기억장치에 들어온 페이지와 교체 / 페이지 부재 증가 (Belady Anomaly)
    LRU - 페이지마다 카운터를 두어 현시점 오랫동안 사용되지 않은 페이지 제거 / Least Recently Used
    LFU - 사용빈도가 적은 페이지를 교체 / Least Frequently Used
    OPT - 가장 오래 사용되지 않을 페이지를 교체 / Belady Min 페이지 교체

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
