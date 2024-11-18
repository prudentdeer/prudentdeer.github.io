---
title: 다형성
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
      I. 다형성 Polymorphism
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 다형성의 정의
        </div>
        <div class="para-cntnt">
            같은 메서드 이름으로, 오버로딩, 오버라이딩 통해 여러 개의 메서드를 만들 수 있는 객체지향 특성
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 다형성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 다형성의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/다형성.png" alt="다형성">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 다형성의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징 오오
  오버라이딩 (overriding) - 하위클래스에서 상위클래스의 메소드를 재정의하여 사용하는 기법
  오버로딩 (overloading) - 동일 클래스의 동일 메소드로 매개변수 다르게 하여 정의하는 기법
장점
  확장성 - 기존 코드(부모 클래스)를 수정하지 않고, 새로운 기능 및 새로운 클래스 추가 쉬움
  유연성 - 실제 실행될 오퍼레이션이 실행 시에 결정. Dynamic Binding
오버라이딩과 오버로딩 비교
  메소드이름 - 같아야 함 &lt;&gt; 같아야 함
  파라미터 개수 - 같아야 함 &lt;&gt; 달라야 함
  자료형 - 같아야 함 &lt;&gt; 같을경우 자료형이 달라야 함
  리턴 타입 - 같아야 함 &lt;&gt; 상관없음
  기타 - 상위 클래스에 메소드 존재 &lt;&gt; 상위 클래스에 같은 이름의 메소드가 없어야 함

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
