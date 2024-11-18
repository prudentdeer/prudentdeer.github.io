---
title: 버퍼 오버플로우
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 보안]
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
      I. 버퍼 오버플로우 공격
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 버퍼 오버플로우의 정의
        </div>
        <div class="para-cntnt">
            연속된 메모리 공간사용 프로그램 할당 메모리범위 초과 오동작 유발 또는 악성코드통한 공격기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 버퍼 오버플로우
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 버퍼 오버플로우의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/버퍼-오버플로우.png" alt="버퍼 오버플로우">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 버퍼 오버플로우의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형
  스택 버퍼오버플로우 - 스택구조상 할당 버퍼 한계치 초과시 복귀주소 변경
  힙 버퍼오버플로우 - 힙구조상 최초 정의 힙사이즈 초과시 데이터, 함수 주소변경
대응방안
  취약함수 금지 - strcpy, ctrcat, getwd, gets, scanf, fscanf, sprintf
  최신 운영체제 사용 - 스택가드, 스택실드 등 여러 장치 있음
  컴파일검사 - 코딩표준, 스택프레임 손상 탐지기능

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
