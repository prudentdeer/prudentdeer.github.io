---
title: 리팩토링
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
      I. Bad Smell 제거, 리팩토링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 리팩토링의 정의
        </div>
        <div class="para-cntnt">
            SW의 외부기능 변경없이, 내부구조 재조정 유지보수성 향상, 기술부채 해소시키는 기법 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 리팩토링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 리팩토링의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/리팩토링.png" alt="리팩토링">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 리팩토링의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          주요기법 RFEM RFED 회귀테스트
  메소드관점
    Rename Method - 이름이 목적을 표현 못할 때 변경     
    Full up Method - 공통된 작업이면 수퍼 클래스로 올림     
    Extract Method - 하나의 클래스가 두개의 작업하면 분리
    Move Method - 다른 클래스에서 더 많이 사용하면 이동     
  설계관점
    Remove Parameter - 불필요한 파라미터 제거     
    Full up field - 공통된 필드를 수퍼 클래스로 올림        
    Encapsulation field - Public 필드를 Private로 만듬     
    Decompose Conditional - 조건 논리를 단순화     
디자인패턴과 리팩토링 비교  
  목적 - 생산성 향상 &lt;&gt; 유지보수성 향상
  대상 - 반복패턴 적용 &lt;&gt; 내부구조 및 로직
  단계 - 상세설계 단계 &lt;&gt; 유지보수 단계
  기법 - 생성, 행위, 구조 패턴 &lt;&gt; Extract, Move, Rename
- 디자인 패턴은 상위수준, 리팩토링은 하위수준 정제

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
