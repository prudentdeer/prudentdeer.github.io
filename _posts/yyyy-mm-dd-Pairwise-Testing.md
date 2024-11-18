---
title: Pairwise Testing
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
      I. 테스트 케이스 도출을 위한 Pairwise Testing
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Pairwise Testing의 정의
        </div>
        <div class="para-cntnt">
            입력 파라미터의 개별 조합을 실행하기 위한 테스트 케이스를 설계하는 블랙박스 테스트 설계기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Pairwise Testing
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Pairwise Testing의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Pairwise-Testing.png" alt="Pairwise Testing">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Pairwise Testing의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  대부분의 결함이 2개 요소의 상호작용에 따라 발생
  필요한 각 값들이 다른 파라미터 값과 최소 한번씩은 조합을 이루는 테스트 케이스 사용
절차 그입페
  그룹선정 - 모든 테스트 케이스 경우의 수 확인
  입력값파악 - 각 그룹 별 선택 가능한 입력 값 대표 값 , 경계 값 ) 파악
  Pair 조합 구성 - 각각 값과 순차적으로 중복되지 않게 배정
한계점
  완벽한 테스트 보장 불가 &gt; 자동화툴, Criticacl Domain

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
