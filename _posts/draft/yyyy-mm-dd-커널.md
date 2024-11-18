---
title: 커널
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 운영체제]
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
      I. 커널
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 커널의 정의
        </div>
        <div class="para-cntnt">
            시스템 HW와 유저 앱 연동위해 자원관리, 스케쥴러, 슈퍼바이저 지원 운영체제의 핵심서비스
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 커널
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 커널의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/커널.png" alt="커널">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 커널의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 모마하엑
  모노리식 커널 - 서비스, 하드웨어 추상화를 묶어 놓은 구조
  마이크로 커널 - 핵심 기능만 커널에서 구현, 나머지 독립적 모듈로 구현
  하이브리드 커널 - 모노리식, 마이크로 장점 수용
  엑소 커널 - 최하의 추상성, 개발자에게 결정권 제공
기능 메프장파
  메모리 관리 - 메모리가 어디에서 무엇을 저장하는 데 얼마나 사용되는지를 추적
  프로세스 관리 - 어느 프로세스가 CPU를 언제 얼마나 오랫동안 사용할지를 결정
  장치 드라이버 - 하드웨어와 프로세스 사이에서 중재자/인터프리터의 역할을 수행
  파일 시스템 - 

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
