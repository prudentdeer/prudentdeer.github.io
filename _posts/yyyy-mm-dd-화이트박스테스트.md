---
title: 화이트박스테스트
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
      I. Logic Driven Test, 화이트박스 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 화이트박스테스트의 정의
        </div>
        <div class="para-cntnt">
            프로그램 명세를 고려하지 않고, 내부구조, 로직기반 테스트 설계, 수행 구조기반테스트
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 화이트박스테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 화이트박스테스트의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/화이트박스테스트.png" alt="화이트박스테스트">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 화이트박스테스트의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          테스트기법, 설계기법 화구제루
  구문 테스트  / 모든 소스커버 : 테스트케이스가 구문을 실행하도록 설계
  제어구조 테스트 / 순차, 선택, 반복 : 프로그램의 처리흐름제어, 수행을 제어 
  루프 테스트 / for, while, goto : 루프구조에 국한해서 실시, 단순루프, 중첩루프, 연결루프 
커버리지 구조결쌍변다
  구문 커버리지 - 모든 구문을 적어도 한번 수행
  조건 커버리지 - 전체결정문 무관, 개별조건이 한번이상 참과 거짓 수행
  결정 커버리지 - 개별조건 무관, 전체결정문이 한번이상 참과 거짓 수행
  조건/결정 커버리지 - 전체 결정, 개별 조건 한번이상 참, 거짓 수행
  변경조건/결정 커버리지 - 같은결과값 얻는것 제외 모든조합 수행
  다중조건 커버리지 - 모든 개별 조건의 모든 가능한 조합 수행
블랙박스와 화이트박스 테스트 비교
  특징 - data driven &lt;&gt; logic driven
  관점 - 사용자 관점 &lt;&gt; 개발자 관점 
  장점 - 테스트케이스가 명확 &lt;&gt; 상세한 테스트 가능
  단점 - 범위가 제한적 &lt;&gt; 테스트케이스 도출 한계
  활용 - 베타 테스트 &lt;&gt; 알파 테스트
- 그레이박스는 편의로 만들어진 용어, SW공학 관점으로 그레이박스는 화이트박스의 한 갈래

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
