---
title: CPU
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
      I. 컴퓨터의 두뇌, CPU
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CPU의 정의
        </div>
        <div class="para-cntnt">
            컴퓨터 명령해독, 논리연산으로 계산속도와 한번에 처리가능한 데이터량이 중요한 두뇌형 장치
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. CPU
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CPU의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/CPU.png" alt="CPU">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. CPU의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  ALU - 각종 산술 연산들과 논리 연산들을 수행하는 회로들로 이루어진 하드웨어 모듈
  레지스터 - CPU 내부에 위치한 Access 속도가 가장 빠른 기억장치
    프로그램 카운터 (PC) - 다음에 인출할 명령어의 주소를 가지고 있는 레지스터
    명령어 레지스터 (IR) - 가장 최근에 인출된 명령어 코드가 저장되어 있는 레지스터
    누산기 (AC) - 데이터를 일시적으로 저장하는 레지스터
    기억장치 주소 레지스터 (MAR) - 명령어 또는 데이터의 주소가 일시적 저장되는 주소
    기억장치 버퍼 레지스터 (MBR) - 기억장치에 쓰여질, 읽혀진 데이터를 일시적으로 저장
  제어장치 - 프로그램 코드(명령어)를 해석하고, 제어 신호들(Control Signals)을 발생 하드웨어 모듈
  CPU 내부버스 주데제
    주소 버스 - CPU가 외부로 발생하는 주소 정보를 전송하는 신호 선들의 집합
    데이터 버스 - CPU가 기억장치 혹은 I/O장치와 의 사이에 데이터를 전송하기 위한 신호선의 집합
    제어 버스 - CPU가 시스템 내의 각종 요소들이 동작을 제어하는데 필요한 신호 선의 집합

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
