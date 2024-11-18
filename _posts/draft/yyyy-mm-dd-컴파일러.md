---
title: 컴파일러
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 소프트웨어공학]
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
      I. 컴파일러
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 컴파일러의 정의
        </div>
        <div class="para-cntnt">
            프로그래밍 언어 소스코드 전체를 실행전에 기계어 변환, Linking, 목적파일 생성하는 프로그램
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 컴파일러
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 컴파일러의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/컴파일러.png" alt="컴파일러">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 컴파일러의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          동작방식
  분석 - 소스 코드를 한 번에 읽어와 해당 언어의 문법 및 구조를 분석
  번역 - 컴파일 시점에 중간 코드 또는 기계 코드로 번역하여 실행파일로 저장
  단점 - 모든파일 초기 스캔시간 소요, 메모리 사용량 큼
  장점 - 빠른 실행속도, 프로그램 실행 전 오류발견
  언어 - 컴파일러 언어 (C, C++, C#, CLEO, COBOL)
* 링킹 - 컴파일러는 기계어로 번역시 오브젝트 코드라는 파일을 만드는데 이 코드를 다시 묶어서 하나의 실행 파일로 다시 만드는 과정

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
