---
title: 선형, 로지스틱 회귀
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 확률과통계]
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
      I. 선형 회귀
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 선형, 로지스틱 회귀의 정의
        </div>
        <div class="para-cntnt">
            종속변수 y 와 한개이상의 독립변수 x와의 선형 상관관계를 모델링하는 회귀분석 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 선형, 로지스틱 회귀
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 선형, 로지스틱 회귀의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/선형,-로지스틱-회귀.png" alt="선형, 로지스틱 회귀">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 선형, 로지스틱 회귀의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형
  단순 선형회귀 - 독립변수가 하나인 경우
  다중 선형회귀 - 설명변수가 2개 이상인 경우의 선형회귀모형
로지스틱 회귀
정의
  데이터를 두개의 그룹으로 분류하기 위해 사용되는, 종속변수 값이 0또는 1인 회귀분석 기법
유형
  다항 로지스틱회귀 - 다수범주를 가지는 문제 대상
  서수 로지스틱회귀 - 다수범주를 가지면서 범주 순서 존재하는 경우 
원리
  승산비 - 성공확률 / 실패확률
  로짓변환 - 입력범위 [−∞,+∞] 일때 출력값 [0,1]로 조정
  로지스틱 함수- x값이 변해도 f(x)는 0과 1 사이의 값을 갖는 함수
선형, 로지스틱 회귀 비교
  문제해결 - 예측문제 &lt;&gt; 분류문제
  종속변수 - 연속형 &lt;&gt; 이산형
  최적화 - 경사하강법 &lt;&gt; 교차 엔트로피
  활성함수 - 선형 &lt;&gt; 시그모이드
  예시 - 흡연율과 사망률관계 &lt;&gt; 주식매도와 보유, 대출 승인과 거절

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
