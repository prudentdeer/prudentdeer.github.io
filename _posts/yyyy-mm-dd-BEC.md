---
title: BEC
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 네트워크]
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
      I. 재전송 통한 오류제어 기법, BEC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. BEC의 정의
        </div>
        <div class="para-cntnt">
            수신 측에서 오류를 검출해 송신측에 알리고, 재전송 요구를 전송하는 오류제어 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. BEC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. BEC의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/BEC.png" alt="BEC">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. BEC의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          주요기법 패순블검
  패리티 검사 - 데이터의 끝에 한 비트를 추가하여 1의 개수로 오류 유무 판단 / 짝스, 홀수
  순환중복 검사 - 이진 나눗셈 연산 및 XOR 연산을 기반으로 오류를 검출하는 방식
  블록합 검사 - 이차원 패리티 검사, 가로와 세로로 두 번 검사
  검사합 검사 - 전송 데이터를 보수화 하여 전송, 수신 측에서는 모드 0 일때 수용하는 검사 방법

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
