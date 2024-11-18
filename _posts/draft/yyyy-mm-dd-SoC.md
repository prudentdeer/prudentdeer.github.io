---
title: SoC
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
      I. 비메모리 집적회로, SoC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SoC의 정의
        </div>
        <div class="para-cntnt">
            PCB 상에서 여러 개의 반도체 칩이 모여 구현되던 시스템이 한 개의 칩으로 집적된 칩
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SoC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SoC의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SoC.png" alt="SoC">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SoC의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            - Printed Circuit Board 
구성요소 FAGA 프기인
  유형 
    FPGA / 프로그래밍 - 설계가능 논리소자와 프로그래밍 가능 내부회로 포함, Field Programmable Gate Array
    ASIC / 주문맞춤형 - 범용 용도가 아닌 특정 용도에 맞게 맞춤 제작된 집적회로, Application Specific Integrated Circuit
    General Purpose IC / 일반화 - 이곳 저곳에 쓸 수 있다. 초고성능이 필요한 분야에서는 안 씀.
    ASSP / 표준화 - 표준화를 해서 이곳 저곳에 쓸 수 있게 만들었다.
  프로세서
    컨트롤러 - 최소한 의 컴퓨팅 요소를 내장한 초소형 컨트롤러
    프로세서 - 중앙 처리 장치(CPU)의 기능을 one chip에 집적해 놓은 IC
  기억장치
    ROM - 읽기 전용 메모리로 정보를 영속적으로 보존하는 메모리 기억매체
    RAM - 프로세서가 빠르게 접근할 수 있도록 하기 위하여, 운영체계, 응용프로그램 그리고 현재 사용중인 데이터를 유지하고 있는 저장 장소
  인터페이스
    IO 인터페이스 - 직렬 주변장치 인터페이스 버스같은 외부 인터페이스
    와이파이, 블루투스
SoC, SiP, SoB 비교
  설계 - 집적처리 &lt;&gt; 집적처리 &lt;&gt; 연결처리
  속도 - 빠름 &lt;&gt; 중간 &lt;&gt; 느림
  인터럽트 - 미존재 &lt;&gt; 존재 &lt;&gt; 존재
- SoB, SiP에서 SoC로 발전

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
