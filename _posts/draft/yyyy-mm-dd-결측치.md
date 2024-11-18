---
title: 결측치
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
      I. Not Applicable, 결측값
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 결측치의 정의
        </div>
        <div class="para-cntnt">
            데이터 수집시 누락되어 적절한 값으로 대체, 삭제가 필요한 Null 데이터 값
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 결측치
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 결측치의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/결측치.png" alt="결측치">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 결측치의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 완무비
  MCAR / 완전무작위 결측 - 변수들과 전혀 무관
  MAR / 무작위 결측 - 측정값들로 추정가능
  MNAR / 비 무작위 결측 - 임의발생이 아님
삭제기법 갑구 확단다
  값삭제
    완전제거 - 하나 결측시 제거
    한쌍제거 - 한쌍 결측시 제거
  구조삭제
    행삭제 - 
    열삭제
대체기법
  확률기반
    핫덱 - 내부 유사데이터 대체
    콜드덱 - 외부 유사 데이터 대체
  단일대체
    연역값 - 논리적제약조건, 유추값 대체
    평균값 - 평균값으로 대체
  다중대체
    MCMC - 몬테카를로 기법 (Markov Chain Monte Carlo)
    GAIN - 적대적 생성망 이용 (Generative adversarial imputation nets)
결측값과 이상값 비교
  특징 - 누락된 값 &lt;&gt; 관측범위 벗어난 값
  검출기법 - is Null &lt;&gt; 통계, 시각화
  처리기법 - 제거법, 단일대체법 &lt;&gt; 분리, 삭제, 대체법, 변환
- 분석가의 주관적 견해가 반영되고 영향력이 큼

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
