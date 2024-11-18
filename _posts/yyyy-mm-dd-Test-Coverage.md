---
title: Test Coverage
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
      I. 테스트 수행 범위의 지표, Test Coverage
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Test Coverage의 정의
        </div>
        <div class="para-cntnt">
            테스트의 정확도를 판단하는 척도로서, 테스트 대상의 전체 범위 중에서 실제 테스트를 수행한 범위
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Test Coverage
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Test Coverage의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Test-Coverage.png" alt="Test Coverage">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Test Coverage의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          커버리지 구조결쌍변다
  구문 커버리지 - 모든 구문을 적어도 한번 수행
  조건 커버리지 - 전체결정문 무관, 개별조건이 한번이상 참과 거짓 수행
  결정 커버리지 - 개별조건 무관, 전체결정문이 한번이상 참과 거짓 수행
  조건/결정 커버리지 - 전체 조건, 개별 조건 한번이상 참, 거짓 수행
  변경조건/결정 커버리지 - 같은결과값 얻는것 제외 모든조합 수행
  다중조건 커버리지 - 모든 개별 조건의 모든 가능한 조합 수행

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
