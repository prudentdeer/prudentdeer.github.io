---
title: DIP, 의존성 역전의 법칙
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
      I. DIP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DIP, 의존성 역전의 법칙의 정의
        </div>
        <div class="para-cntnt">
            변화가 쉬운 구체클래스에 의존하지 않고 변화가 없는 추상화에 의존 객체지향 설계원칙
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DIP, 의존성 역전의 법칙
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DIP, 의존성 역전의 법칙의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DIP,-의존성-역전의-법칙.png" alt="DIP, 의존성 역전의 법칙">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DIP, 의존성 역전의 법칙의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구현방법 추인오변
  설계
    추상팩토리 사용 - 변동성이 큰 구체 클래스를 참조 금지
    인터페이스 상속 - 추상 클래스로부터 파생
  구현
    오버라이드 금지 - 구체 함수로 오버라이드 금지
    변동성 의존금지 - 자주변경되는 클래스 의존금지
DIP 와 DI 비교
  개념 - 추상화에 의존 &lt;&gt; 외부에서 제어가능성
  모듈관계 - 모듈 사이의 추상화 &lt;&gt; 외부에서 제공
  적용방법 - 추상화 &lt;&gt; 의존성을 주입
  장점 - 유연, 확장성 &lt;&gt; 유지보수 용이

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
