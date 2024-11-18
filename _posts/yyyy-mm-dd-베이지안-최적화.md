---
title: 베이지안 최적화
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
      I. 하이퍼파라미터 튜닝기법, 베이지안최적화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 베이지안 최적화의 정의
        </div>
        <div class="para-cntnt">
            머신러닝 성능향상위해, 대체모델과 획득함수를 활용한 하이퍼파라미터 최적화 튜닝기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 베이지안 최적화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 베이지안 최적화의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/베이지안-최적화.png" alt="베이지안 최적화">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 베이지안 최적화의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  Surrogate Model = estimation function - 현재까지 조사된 값으로, 추정 수행하는 모델
  Object Function - 탐색대상함수
  Acquisition Function - 최적 입력값을 찾는 데 있어 가장 유용할 만한 다음 입력값 추천
프로세스 대목추획
  대체모델생성 – 조사된 입력값-함숫결과 기반
  목적함수추정 – 대체모델으로 미지의 목적함수 추정
  추정함수갱신 – 관측된 값을 기반으로 추정함수 업데이트
  획득함수추천 - 획득함수 최대값 기반 다음 입력값 탐색
- 베이지안의 느린속도를 보완한 Hyperband 기법 존재

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
