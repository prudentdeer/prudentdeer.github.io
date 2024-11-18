---
title: 악성코드 탐지
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
      I. 악성코드 탐지기술
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 악성코드 탐지의 정의
        </div>
        <div class="para-cntnt">
            시그니처 분석 스씨명바
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 악성코드 탐지
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 악성코드 탐지의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/악성코드-탐지.png" alt="악성코드 탐지">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 악성코드 탐지의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
              스트링 시그니처 - 파일에 포함되어 있는 문자열을 시그니처 이용하여 분석
    CFG 시그니처 - 코드섹션의 실행 흐름과 구조를 표현하는 Control Flow Graph 분석
  코드 분석 
    명령어 빈도수 - 악성코드로 밝혀진 파일로부터 사용되는 명령어를 추출, 빈도수 분석
    바이트 시퀀스 - 바이너리 파일 포함된 바이트 시퀀스를 이용하여 시그니처 생성, 비교
동적분석 기반 에샌무행
  실행기반
    에뮬레이터 - 가상환경 기반에서 프로그램을 먼저 실행
    샌드박스 - 실제 컴퓨터 시스템 상에서 프로그램을 실행
  탐지기반
    무결성 검사 - 데이터, 실행시스템에 대해 변화가 없이 유지되는지 확인
    행위 추적 - 악성코드 유사행위 발생시 프로그램을 추적하여 차단

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
