---
title: MVP
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
      I. MVP 패턴
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MVP의 정의
        </div>
        <div class="para-cntnt">
            뷰와 모델을 분리하고 Presenter 가 상호작용 해줌으로써 의존성 최소화하는 패턴
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MVP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MVP의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MVP.png" alt="MVP">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MVP의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  Model - 데이터를 저장하고 처리하는 계층
  View - 사용자가 직접 보는 화면(UI)을 담당하는 계층
  Presenter - 뷰와 모델을 완전히 분리하고 서로간의 의존성 제거
흐름
  1. 사용자의 Action을 View에서 받습니다. (사용자 Action → View)
  2. View에서는 Presenter로 요청을 합니다. (View → Presenter)
  3. Presenter에서는 Model로 데이터를 요청합니다(Presenter → Model)
  4. Model은 Presenter로 데이터를 전달합니다.(Model → Presenter)
  5. Presenter는 View에게 데이터를 전달합니다.(Presenter → View)
  6. View에서 사용자로 화면을 보여줍니다.(View → 사용자)

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
