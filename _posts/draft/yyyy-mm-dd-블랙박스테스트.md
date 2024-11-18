---
title: 블랙박스테스트
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
      I. Data Driven Test, 블랙박스 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 블랙박스테스트의 정의
        </div>
        <div class="para-cntnt">
            프로그램의 구조를 고려하지 않고, SRS, 명세서 기반 테스트 설계, 수행 블랙박스테스트
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 블랙박스테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 블랙박스테스트의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/블랙박스테스트.png" alt="블랙박스테스트">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 블랙박스테스트의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          테스트기법, 설계기법 블동경의상 유분페원
  동등 분할기법 - 유사한 특징으로 분류, 대표 테스트케이스를 작성
  경계값 분석기법 -  중간값보다 경계값에서 에러발생 확률이 높다는 이론을 이용
  의사결정 테이블 - 명세서를 이용하여 조합관계를 생성
  상태전이 - 상태전이 다이어그램 기반으로 시스템 동작을 확인하는 기법
  유즈케이스 - 유즈케이스 명세서를 기반으로 테스트 시나리오 구성
  분류 트리 - 흐름을 트리 구조로 표현하여 테스트 케이스 설계
  페어와이즈 조합 - 값들이 서로 한번씩 조합을 이루도록 테스트
  원인결과 - 여러 원인을 분석하여 테스트 수행

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
