---
title: 테스트 오라클
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
      I. 미리 정의된 참값과 결과비교, 테스트오라클
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 테스트 오라클의 정의
        </div>
        <div class="para-cntnt">
            테스트 수행 결과가 참, 거짓인지 판단위해 미리 정의된 참을 대입하여 실제결과와 비교하는 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 테스트 오라클
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 테스트 오라클의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/테스트-오라클.png" alt="테스트 오라클">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 테스트 오라클의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 참샘휴일
  참 오라클 / 모든 입력값 - 모든 테스트 케이스 입력 값의 기대한 결과값에 대한 확인&nbsp;
  샘플링 오라클 / 특정 입력값 - 특정 입력 값들에 대해서만 원하는 결과를 제공
  휴리스틱 오라클 / 몇몇 입력 - 몇몇 입력은 샘플링 오라클과 같은 결과 제공, 나머지 입력은 휴리스틱 처리
  일관성검사 오라클 / 이전, 이후검사 - 이전 수행 결과와 현재 수행 결과가 동일한지 검증
참 오라클 &lt;&gt; 샘플링 오라클 &lt;&gt; 휴리스틱 오라클 비교
  커버리지 - 모든케이스 &lt;&gt; 일부케이스 &lt;&gt; 중간
  장점 - 높은 정확도 &lt;&gt; 작성 용이 &lt;&gt; 적용 용이
  단점 - 개발비용 &lt;&gt; 검증안됨 &lt;&gt; 검증안됨
- 항공기, 선박 mission critical SW는 참오라클 사용

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
