---
title: MVVM
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
      I. MVVM 패턴 - vue, react
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MVVM의 정의
        </div>
        <div class="para-cntnt">
            모델, 뷰, 뷰 모델로 기능을 분리하고, Data binding 통해 뷰와 뷰모델 간 양방향 통신 패턴
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MVVM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MVVM의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MVVM.png" alt="MVVM">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MVVM의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  Model - 어플리케이션에서 사용되는 데이터와 그 데이터를 처리
  View - 사용자에게 보여지는 UI
  View Model - View를 나타내 주기 위한 Model이자 데이터 처리
  Data Binding - View에 해당하는 xml파일과 데이터를 연결하여서 하나로 묶는 작업
흐름
  1. 사용자가 입력한 값이 View를 통해 들어옵니다. (사용자 → View)
  2. View에 입력값이 들어오면 ViewModel로 입력 값을 전달합니다. (View → ViewModel)
  3. 전달받은 ViewModel은 Model에게 데이터 요청을 보냅니다. (ViewModel → Model)
  4. Model은 ViewModel에게 요청받은 데이터를 Response 합니다(ViewModel ← Model)
  5. ViewModel은 그 값을 처리하여 내부에 저장합니다.
  6. View는 ViewModel과의 ‘데이터 바인딩’을 통해 화면상에 표출합니다.(View ↔︎ ViewModel)

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
