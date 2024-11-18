---
title: 유한 오토마타(Finite Automata)
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
      I. [정의] 컴퓨터 프로그램과 전자논리 회로를 설계하는데 쓰이는 이산적인 입력과 출력을 가지는 
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 유한 오토마타(Finite Automata)의 정의
        </div>
        <div class="para-cntnt">
          [용어] 단일상태: 한번에 하나의 상태, 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 유한 오토마타(Finite Automata)
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 유한 오토마타(Finite Automata)의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/유한-오토마타(Finite-Automata).png" alt="유한 오토마타(Finite Automata)">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 유한 오토마타(Finite Automata)의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          전이(transition): 사건에 의해 상태 변화, 상태(state): 전이 시작을 위한 시스템의 행동적 노드(진입동작, 퇴장동작) 
[활용] HW부문(디지털회로 설계), SW부문(응용 프로그램 설계, 컴파일러 설계)
[유형]
결정적 유한 오토마타(DFA): 모든 상태는 각각의 가능한 입력에 대해 정확히 하나의 변화된 상태를 가질수 있는 유한 오토마타
비결정적 유한 오토마타(NFA):입력은 주어진 상태에 대해 한가지 또는 여러가지 변환된 상태를 가질수 있는 유한 오토마타

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
