---
title: 컨텐츠 필터링
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 인공지능]
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
      I. 컨텐츠 필터링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 컨텐츠 필터링의 정의
        </div>
        <div class="para-cntnt">
            아이템, 서비스의 내용, 속성, Feature 분석하고 유사도, 선호도기반 추천 필터링기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 컨텐츠 필터링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 컨텐츠 필터링의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/컨텐츠-필터링.png" alt="컨텐츠 필터링">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 컨텐츠 필터링의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유사도 기법 유코피자
  벡터기반
    유클리드 거리 - 점과 점의 최단거리 계산
    코사인 유사도 - 두 벡터간 코사인 값 유사한 정도
  관계기반
    피어슨 유사도 - 두 벡터간 상관계수를 계산
    자카드 유사도 - 두 집합의 합집합에서 교집합 비율을 비교하여 산출
장점
  개인 데이터로 추천 - 다른 사용자의 데이터가 없어도 추천 가능
  신규 아이템 추천 - 아이템 설명만으로 신규 아이템, 평점이 낮은 아이템도 추천
단점
  필터버블 - 정보제공자가 개인 성향에 맞춘 정보만을 제공하여 버블안에 가두는 현상
  주관성 개입 - 사용자의 아이템에 대한 주관이 추천에 개입 가능
- 편협한 범위고정 필터버블이 발생할 가능성이 매우 높음

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
