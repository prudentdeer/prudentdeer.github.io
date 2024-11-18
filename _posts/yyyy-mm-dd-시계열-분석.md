---
title: 시계열 분석
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
      I. 미래예측 분석, 시계열분석
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 시계열 분석의 정의
        </div>
        <div class="para-cntnt">
            시간의 흐름에 따라 기록된 자료의 특성을 파악하여 미래를 예측하는 분석기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 시계열 분석
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 시계열 분석의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/시계열-분석.png" alt="시계열 분석">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 시계열 분석의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          분석기법
  일변량
    Box-Jenkins - 자동회귀이동평균 모델을 적용하여 시계열 과거 값에 대한 시계열 모델 
    지수 평활법 - 과거의 모든 자료를 사용하여 평균을 구하면서 최근의 자료에 더 높은 가중치를 부여
    시계열 분해법 - 시계열에 영향을 주는 일반적인 요인을 시계열에서 분리해 분석
다변량
    계량경제 모형 - 시계열 데이터에 대한 회귀분석
    전이함수 모형 - 입/출력 시계열들 사이의 관계를 회귀모형의 형태로 표현
    개인분석 - 사건이 언제 발생했는지를 아는 경우 모형화 한 후 효과 추정 및 유의성 여부 판단
    상태공간 모형 - 시계열 생성 구조를 상태 전이식과 관측식 두개의 수식으로 정의
영향요인 추순계불
  추세요인 - 인구 변화, 자원 변화 등 장기 변동 요인  
  순환요인 - 경제활동의 팽창, 위축과 같이 불규칙적이며 반복적인 중기 변동
  계절요인 - 12개월의 주기를 가지고 반복되는 변화를 말함    
  불규칙요인 - 일정한 규칙성을 인지할 수 없는 변동의 유형을 의미

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
