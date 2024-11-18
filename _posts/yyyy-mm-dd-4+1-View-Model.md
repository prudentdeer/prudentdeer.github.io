---
title: 4+1 View Model
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
      I. SW Architecture를 구성하는 View
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 4+1 View Model의 정의
        </div>
        <div class="para-cntnt">
            SW 아키텍처에 대해 이해관계자들의 관심에 따라 서로 다른 4가지 뷰로 표현한 아키텍처의 모델
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 4+1 View Model
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 4+1 View Model의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/4+1-View-Model.png" alt="4+1 View Model">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 4+1 View Model의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 유논구프배
  유즈케이스 관점 / 사용자 - 사용자 기능
  논리적 관점 / 분석, 설계자 - 클래스나 컴포넌트의 종류와 관계
  구현 관점 / 프로그래머 - 서브시스템 모듈구조와 관계
  프로세스 관점 / 통합자 - 시스템의 성능, 확장성, 효율
  배치 관점 / 엔지니어 - 시스템의 구성
- 시나리오란 고객의 요구 만족시키기 위해 시스템이 사용자와 상호 작용하는 방법
- 유스케이스 하나가 표현하는 요구사항을 만족시키려면 4개 뷰가 합심
- 4 +1이라는 것은 유스케이스가 나머지 4개 뷰에 모두 참여하면서 영향을 준다는 뜻

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
