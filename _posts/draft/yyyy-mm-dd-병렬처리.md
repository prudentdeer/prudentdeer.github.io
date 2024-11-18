---
title: 병렬처리
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
      I. [병렬컴퓨팅 문제] 분할, 동기화, 스케쥴링, 캐시메모리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 병렬처리의 정의
        </div>
        <div class="para-cntnt">
          분할문제(병렬성 탐지, 묶음)
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 병렬처리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 병렬처리의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/병렬처리.png" alt="병렬처리">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 병렬처리의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          스케줄링문제(정적스케줄링-컴파일시, 동적스케줄링-수행시)
동기화문제(버스잠금,플래그기법,세마포어기법,모니터)
캐시메모리문제(공유cache사용, 공유변수cache 미사용,하나의 버스통한 병목)
[유형]
[Flynn의 분류] SISD, SIMD, MISD, MIMD
[메모리 공유] SMP, MPP, NUMA
[CPU 유형에 따른 분류] CISC, RISC, EISC, EPIC
[팽(Feng)의 분류] WSBS(Word serial, bit serial), WSBP(word serial, bit parallel),
WPBS(word parallel, bit serial), WPBP(word parallel, bit parallel

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
