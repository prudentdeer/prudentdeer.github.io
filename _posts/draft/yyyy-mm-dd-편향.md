---
title: 편향
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
      I. AI의 공정성 훼손, 편향
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 편향의 정의
        </div>
        <div class="para-cntnt">
            데이터, 외부 환경요인으로 인공지능 시스템이 특정방향에 치우친 결과를 도출하는 현상
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 편향
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 편향의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/편향.png" alt="편향">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 편향의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          편향의 종류 인숨데롱고
  데이터요인
    인간의 편향 - 인간으로부터 기인한 원시 데이터 자체에 편향
    숨겨진 편향 - 절대 보거나 발견될수 없는 의도하지 않는 편향
    데이터 편향 - 시스템에 공급되는 데이터에 샘플링 편향
  외부환경요인
    롱테일 편향 - 훈련 데이터에서 특정 범주가 누락될 때 발생
    고의적 편향 - 해킹 공격을 통해 인공지능이 의도적으로 편향
편향 완화방법 학모튜
  학습데이터 / 필터링, 전처리 - 근원적인 편향, 내재적인 편향 제거
  모델링작업 / 보호변수, 앙상블 - 편향성과 관련이 있는 변수 조정 , 적대적 편향 제거, AI 학습 중에 약간의 수정
  튜닝 / 하이퍼파라미터 - 분류자나 학습 데이터 대신 모델의 결과만 조정
높은편향 - 과소적합
낮은편향 - 과대적합

역사적편향 - 과거의 경험과 데이터가 변화된 현재의 상황을 이해하는데 영향을 끼침
대표성편향 - 수집한 표본이 수집자의 환경으로 인해 모집단의 특성을 반영하지 못하여 발생
측정편향 - 측정도구나 방법의 오류로 측정결과가 치우치게 나옴
모집단편향 - 샘플 데이터의 분포가 모집단의 분포와 다를 때 발생
표본추출편향 - 하위집단의 랜덤하지 않은 표본 추출로 인해 발생
순위편향 - 상위권의 정보가 상대적으로 과다하게 선택되는 결과

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
