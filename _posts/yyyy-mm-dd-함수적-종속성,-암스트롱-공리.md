---
title: 함수적 종속성, 암스트롱 공리
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 데이터베이스]
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
      I. 함수 종속성 추론 원리, 함수적 종속성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 함수적 종속성, 암스트롱 공리의 정의
        </div>
        <div class="para-cntnt">
            릴레이션 속성 부분집합 X, Y에 대해 결정자 X에 따라, 종속자 Y값이 오직 하나만 연관되는 성질
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 함수적 종속성, 암스트롱 공리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 함수적 종속성, 암스트롱 공리의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/함수적-종속성,-암스트롱-공리.png" alt="함수적 종속성, 암스트롱 공리">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 함수적 종속성, 암스트롱 공리의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          추론규칙 재부이 분합의
  기본규칙
    재귀성 규칙 - Y⊆ X 이면  X → Y
    부가성 규칙 - X  → Y 이면 XZ → YZ
    이행성 규칙 - X → Y 이고, Y → Z 이면 X → Z
  부가규칙
    분해규칙 - X → YZ 이면, X → Y, X → Z
    합집합규칙 - X → Y 이고, X → Z 이면, X → YZ
    의사이행규칙 - X →&nbsp;Y 이고, WY →&nbsp;Z 이면, XW →&nbsp;Z
정규화 적용
  재귀규칙 / 제1정규화 - 중복제거
  부가규칙 / 제2정규화 - 부분함수 종속제거
  이행규칙 / 제3정규화 - 이행함수 종속제거
  완전함수 종속성 : X’⊂X 이고  X’→Y 를 만족하는 애트리뷰트 X' 이 존재하지 않음 / 정규화 미대상
  부분함수 종속성 : X’⊂X 이고  X’→Y 를 만족하는  애트리뷰트 X' 이 존재함, 제2 정규화 필요
  이행함수 종속성 : 릴레이션 R 에서 속성 A→X 이고 X→Y 이면 A→Y 임, 제 3정규화 필요
  결정함수 종속성 : X→Y 에서 X 가 후보키가 아님, BCNF 필요
  다중값 종속성 : X, Y, Z 세개의 속성을 가진 릴레이션 R에서 속성쌍[X,Z]값에 대응하는 Y값의 집합이 X값에만 종속되고 Z값에는 독립, 4NF 필요
  조인 종속성 : 관계 중 둘로 나눌때는 원래의 관계로 회복할 수 없으나, 셋 또는 그 이상으로 분리할때 복원가능한 경우, 5NF

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
