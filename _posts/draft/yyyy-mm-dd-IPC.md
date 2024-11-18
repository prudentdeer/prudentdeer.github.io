---
title: IPC
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
      I. 프로세스 간 상호 정보 교환, IPC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IPC의 정의
        </div>
        <div class="para-cntnt">
            독립된 프로세스간 데이터 공유위해 메모리 큐, 파이프, 소켓 이용 데이터 송수신 메커니즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IPC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IPC의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IPC.png" alt="IPC">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IPC의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 메공세파소
  메시지 큐 - Kernel 내부에서 Message Queue 이용
  공유 메모리 - 두 개 이상의 프로세스가 특정한 메모리 영역을 공유
  세마포어 - 임계영역 진입을 위해 대기, 동기화 문제 해결
  파이프 - 프로세스 간에 파이프 단방향 통신 채널 구성
  소켓 - 운영체제에서 제공하는 가상 통신 포트

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
