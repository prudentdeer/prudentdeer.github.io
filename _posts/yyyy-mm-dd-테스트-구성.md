---
title: 테스트 구성
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
      I. 테스트 베드
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 테스트 구성의 정의
        </div>
        <div class="para-cntnt">
          테스트 하네스
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 테스트 구성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 테스트 구성의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/테스트-구성.png" alt="테스트 구성">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 테스트 구성의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            테스트 지원하기 위해 시스템 및 컴포넌트 테스트 환경의 일부분으로 생성된 코드와 데이터
테스트 드라이버 상드 (타겟기준 상향)
  하위 컴포넌트는 존재하지만 상위 컴포넌트가 없는 경우의 상향식 더미모듈
테스트 스텁 하스 (타겟기준 하향)
  상위 컴포넌트는 존재하지만 하위 컴포넌트가 없는 경우의 하향식 더미모듈

드라이버와 스텁 비교
  테스트방식 - 상향식 &lt;&gt; 하향식
  공통점 - 개발과 테스트 병행 시 이용
  차이점 - 하위모듈 존재, 상위모듈 미존재 &lt;&gt; 상위모듈 존재, 하위모듈 미존재

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
