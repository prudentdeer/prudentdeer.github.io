---
title: UML 관계
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
      I. UML 구성요소 관계정의, UML 관계
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. UML 관계의 정의
        </div>
        <div class="para-cntnt">
            UML 구성요소간 관계를 나타내기위해 4가지유형과 길러멧, 스테레오타입 이용한 관계표기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. UML 관계
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. UML 관계의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/UML-관계.png" alt="UML 관계">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. UML 관계의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          관계유형 연의GR 연직집복 의확포일실
  연관관계 - 서로에 대한 참조 관계를 가짐
    직접연관 관계 - 클래스가 개념적으로 서로 연관
    집함연관 관계 - 전체 소멸시 부분은 사용가능
    복합연관 관계 - 전체 소멸시 부분도 같이소멸
  의존관계 - 클래스 변화, 다른클래스에도 변화
    확장의존 관계 - 클래스 변화가 타클래스 영향, 선택적 확장하는 관계
    포함의존 관계 - 클래스 변화가 타클래스 영향, 반드시 포함하는 관계
  일반화 관계 - 자식이 부모속성 물려받음, 상속
  실체화 관계 - 인터페이스와 구체클레스 관계
UML의 길러멧과 스테레오타입
  길러멧 / &lt;&lt; &gt;&gt; - 기호 사이에 스테레오 타입의 특성을 정의
  스테레오타입 / 확장요소 - UML 기본요소 외 추가적 확장요소 정의, Interface, abstract

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
