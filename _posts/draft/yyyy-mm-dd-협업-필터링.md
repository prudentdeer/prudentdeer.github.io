---
title: 협업 필터링
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
      I. 협업 필터링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 협업 필터링의 정의
        </div>
        <div class="para-cntnt">
            다른 사용자들로부터 누적된 기호정보 분석하고 유저, 아이템, 모델기반 추천 필터링기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 협업 필터링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 협업 필터링의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/협업-필터링.png" alt="협업 필터링">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 협업 필터링의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 유아클리
  메모리기반
    User Based - 나와 유사한 성향 사람 기반, 그 사람들의 성향의 유사도 측정하여 추천
    Item Based - 내가 선호하는 아이템 기반, 아이템의 유사도 측정하여 추천
  모델기반
    Classification - 유저의 성향에 따라 군집을 분류 
    Regression - 유저와 아이템에 대한 평균 평점모델 
장점
  필터버블 개선 - 폭넓은 추천 pool 제공
  Domain Free - 관련된 지식 불필요
단점
  콜드스타트 - 충분한 정보를 모으지 못하면 추천을 할 수 없는 한계
  롱테일 문제 - 관심이 저조한 아이템은 추천되지 못하고, 다양성이 떨어지는 문제가 발생
- 타 데이터 부족시 콜드스타트, 롱테일 문제 한계존재

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
