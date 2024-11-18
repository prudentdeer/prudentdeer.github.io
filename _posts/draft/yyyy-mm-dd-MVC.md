---
title: MVC
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
      I. 재사용 향상을 위한 MVC 패턴 - Spring
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MVC의 정의
        </div>
        <div class="para-cntnt">
            모델, 뷰, 컨트롤러 분리하고 사용자 인터페이스로부터 비즈니스 로직을 분리하는 패턴
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MVC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MVC의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MVC.png" alt="MVC">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MVC의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            특징) 결합도 최소화, 확장성, 유지보수 용이성
구성요소
  Model - 모든 데이터의 상태와 로직 처리 / 데이터베이스, 파일
  View - 데이터 표시 및 사용자입력 처리 / HTTP, CSS, Javascript
  Controller - 모델과 뷰 사이의 중개자 역할 / 기능수행과 뷰 연결
흐름 
  1. 사용자의 Action을 Controller에서 받습니다. (사용자 Action → Controller)
  2. Controller에서는 이를 확인하고 Model을 업데이트 수행합니다.(Controller → Model)
  3. 수정된 값을 Controller로 반환합니다.(Controller ← Model)
  4. Controller에서는 View의 수정합니다.(View ← Controller)
  5. 사용자에게 변경된 화면을 반환합니다.(사용자 Action ← View)

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
