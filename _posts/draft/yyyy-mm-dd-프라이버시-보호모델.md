---
title: 프라이버시 보호모델
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 보안]
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
      I. 재식별 방지를 위한 프라이버시 보호모델
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 프라이버시 보호모델의 정의
        </div>
        <div class="para-cntnt">
            비식별화된 개인정보의 재식별을 방지하기 위해 개인 식별요소를 제거, 방지하는 보호모델
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 프라이버시 보호모델
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 프라이버시 보호모델의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/프라이버시-보호모델.png" alt="프라이버시 보호모델">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 프라이버시 보호모델의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 연익 동배다 쏠유근 재유
  K 익명성 / 동일 값 레코드 K개 이상 - 특정인임을 추론할 수 없는 비식별 조치 기법
  L 다양성 / L이상 다양성 확보 - 민감정보 다양성을 높여 추론 가능성을 낮추는 기법
  T 근접성 / 전체, 특정 분포 차이 T 이하 - 분포를 낮추어 추론 가능성을 더욱 낮추는 기법
  M 유일성 / 동일한 속성 값의 조합 m개 이하 - 
공격기법
  연결공격 / K-익명성 - 다른공개 데이터간 결합을 통해 개인 식별
  동질성 / L-다양성 - 동일한 정보를 이용하여 대상의 정보 파악
  배경지식 / L-다양성 - 공격자의 배경지식을 통해 민감정보 알아내는 공격
  쏠림 / T-근접성 - 특정한 값에 쏠려있는 경우 추론가능
  유사성 / T-근접성 - 의미상 유사하다면 민감정보 유추가능
  재식별 / M-유일성
- 민감데이터에 대해서는 합성데이터, 차분프라이버시 모델 적용 고려

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
