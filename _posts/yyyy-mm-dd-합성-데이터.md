---
title: 합성 데이터
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
      I. 개인정보보호, 합성데이터
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 합성 데이터의 정의
        </div>
        <div class="para-cntnt">
            개인정보보호와 데이터 부족 해결위해 모집단 기반, 알고리즘을 통해 생성하는 임의데이터
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 합성 데이터
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 합성 데이터의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/합성-데이터.png" alt="합성 데이터">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 합성 데이터의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          합성 데이터의 분류 완부복
  완전 합성데이터 - 실제데이터가 없이 모두 가상 데이터로 생성
  부분 합성데이터 - 일부의 실제데이터와 가상 데이터 혼합
  복합 합성데이터 - 부분 합성데이터를 또 다시 합성하여 생성
기술
  임베딩 - 두 개의 신경망(인코더와 디코더)을 사용하여 데이터를 생성
  GAN - 판별자는 생성자가 생성한 레코드를 실제 데이터와 구별하려는 시도를 하면서 학습하고 성향 점수를 제공
  순차적 합성 - 변수별로 데이터 세트 변수를 합성하는 방법
  VAE - 확률 분포를 통해 유사 데이터 생성
  Stable Diffusion - 텍스트 프롬프트를 입력하면, 그 텍스트에 맞는 이미지를 생성하여 반환하는 모델
AI 프라이버시 이슈
  연합학습의 문제점 - 파라미터로부터 학습데이터를 복원하는 공격법 존재
  합성데이터 문제점 - 프라이버시가 보호된다고 착각, 원본과 같은 통계적 분포, 민감정보 추론가능
  &gt; 근본적 해결방안이 존재하지 않음, 지속적 관심과 대비가 필요

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
