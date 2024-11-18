---
title: CPU Major 상태
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
      I. CPU의 4가지 작업상태, 중앙처리장치의 메이저 상태
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CPU Major 상태의 정의
        </div>
        <div class="para-cntnt">
            CPU가 현재 수행하는 4가지 형태 Fetch, Indirect, Execute, Interrupt 의 작업 상태
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. CPU Major 상태
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CPU Major 상태의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/CPU-Major-상태.png" alt="CPU Major 상태">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. CPU Major 상태의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  CPI는 4가지 상태를 반복적으로 수행, 메이저 상태 레지스터를 통해 확인
메이저상태 유형 인간실인
  Fetch / 인출 - 명령어를 가져와서 해독
  Indirect / 간접 - 간접 주소인 경우 수행
  Execute / 실행 - 해석한 명령을 실행
  Interrupt / 인터럽트 - Interrupt 발생시 제어순서를 인터럽트 처리프로그램의 첫번째 명령으로 옮기는 단계
메이저상태 변화과정
  직접주소 사용시 - 인출 → 실행 
  간접주소 사용시 - 인출 → 간접 → 실행 
  인터럽트 발생시 - 인출 → 간접 → 실행 → 인터럽트 발생 → 인터럽트 → 인출 

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
