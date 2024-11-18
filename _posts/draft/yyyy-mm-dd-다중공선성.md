---
title: 다중공선성
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
      I. 강한 상관관계에 따른 문제, 다중공선성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 다중공선성의 정의
        </div>
        <div class="para-cntnt">
            다중회귀분석에서 독립변수간 상관도가 높아 데이터 분석시 부정적인 영향을 미치는 현상
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 다중공선성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 다중공선성의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/다중공선성.png" alt="다중공선성">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 다중공선성의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  상관관계 - 다중회귀분석에서 두개 이상의 독립변수 간에 높은 상관관계
  예측력 저하 - 다중공선성이 높은 모델은 데이터에 대한 예측력이 저하
상세설명 결상분 변주다
  판단기준
    결정계수 - 종속변인과 독립변인 사이에 상관관계가 높을수록 1에 가까워짐
    상관계수 - 독립변수들간의 상관계수 도출 보통 0.7이상일 경우 상관관계가 높다고 판단
    분산팽창요인 - VIF = 1/1-r 이 값이 10을 넘는다면 보통 다중공선성의 문제가 있다고 판단
  해결방법
    변수제거 - 상관 관계를 가지는 두 변수 중 하나를 제거
    주성분 분석(PCA) - 주성분 변수는 서로 독립이므로 문제 발생 소지 감소
    다른모델 사용 - MSE 최소화 추정 방법을 사용하여 다중공선성문제 해결
- 다중공선성은 예측력저하와 표준오차증가 유발

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
