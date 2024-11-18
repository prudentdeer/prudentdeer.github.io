---
title: 몬테카를로
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
      I. 난수와 반복 확률계산, 몬테카를로방법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 몬테카를로의 정의
        </div>
        <div class="para-cntnt">
            문제 해결위해 난수 데이터와 반복 시뮬레이션 통해 근사적 해를 추정하는 알고리즘 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 몬테카를로
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 몬테카를로의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/몬테카를로.png" alt="몬테카를로">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 몬테카를로의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          절차
  샘플링관점
    문제정의 - 입력값, 변수범위, 목표설정
    난수샘플추출 - 난수 발생기 사용 샘플생성
    시뮬레이션 - 무작위 샘플통한 모델링
  분석관점
    결과수집/계산 - 근사치 결과데이터 분석
    에러분석/해석 - 신뢰도위한 에러분석
    반복 - 정확도 위한 과정반복
몬테카를로와 마르코프 몬테카를로 비교
  샘플링 - 무작위 샘플링 &lt;&gt; 마르코프 체인
  재사용 - 독립추출 &lt;&gt; 이전샘플 의존
  활용 - 다양한 분야 &lt;&gt; 베이지안 및 추론
- 확률모형을 적용할 수 있는 다양한 분야의 문제에 활용

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
