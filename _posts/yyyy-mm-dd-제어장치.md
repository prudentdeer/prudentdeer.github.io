---
title: 제어장치
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
      I. CPU의 명령어 장치, 제어장치
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 제어장치의 정의
        </div>
        <div class="para-cntnt">
            프로그램 명령어를 해석하고, 실행하기 위한 제어 신호를 순차발생, 전달하는 CPU 구성요소
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 제어장치
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 제어장치의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/제어장치.png" alt="제어장치">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 제어장치의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          Micro-Programmed 
  X86
  정의 - 제어신호 조합을 미리 구성해 프로그램으로 저장하여 필요시 신호발생하는 방식 (CISC)
  구현방법 세집매제
    설계
      명령어세트 설계 - 각 명령어에 대한 동작과 제어 신호를 정의
      명령어집합 설계 - 프로그램을 작성하기 위해 마이크로 명령어 집합을 설계
      프로그램 작성 - 마이크로 명령어 집합과 명령어별로 제어 프로그램 작성 
    구현 
      메모리 구현 - ROM 또는 RAM 으로 구현 
      제어유닛 통합 - 마이크로 프로그램이 마이크로 메모리에 저장되면, 제어 유닛과 통합 
    최적화 
      디버깅 및 최적화 - 구현된 마이크로 프로그램을 디버깅하고 최적화하는 과정을 수행
Hard-Wired
  ARM
  정의 - 제어장치의 기능을 조합논리회로를 이용하여 Hardwire로 구현하는 방식 (RISC)
  구현방법 세논제회
    설계
      명령어세트 설계 - 명령어는 특정 동작을 수행하도록 설계
      유한상태 기계설계 - 시스템이 특정 상태에서 다른 상태로 전이하도록 제어하는데 사용
      논리회로 설계 - 명령어의 동작을 구현하기 위해 논리 게이트를 사용해 설계
    구현
      제어신호 생성 - 각 명령어에 대한 제어신호 생성
      회로통합 - 설계한 논리 회로를 통합하여 전체 제어 유닛을 형성 
    최적화
      디버깅 및 최적화 - 완성된 하드웨어 제어 유닛을 디버깅하고 최적화하는 과정 
비교 구유명복 속디비유
  구현 - 마이크로 코드 &lt;&gt; 논리 게이트 및 회로
  유연성 - 높음 &lt;&gt; 낮음
  명령어 - 복잡한 명령어 &lt;&gt; 제한된 명령어
  복잡성 - 구현 어려움 &lt;&gt; 구현 용이
  속도 - 디코딩으로 인해 느림 &lt;&gt; 빠른 작동 
  디버깅 - 쉬움 &lt;&gt;  어려움 
  비용 - 높은 비용 &lt;&gt; 낮은 비용 
  유지관리 - 쉬움 &lt;&gt; 어려움

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
