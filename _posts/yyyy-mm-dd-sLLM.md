---
title: sLLM
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
      I. AI의 민주화, sLLM 모델
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. sLLM의 정의
        </div>
        <div class="para-cntnt">
            LLM 모델의 컴퓨팅 파워, 비용문제 해결위해 파라미터 수 줄이고 파인튜닝 적용 경량 언어모델
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. sLLM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. sLLM의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/sLLM.png" alt="sLLM">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. sLLM의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징  
  60~70억 파라미터 / Fine Tuning / 비용 절감 / 신속한 구축가능
매커니즘 구사평배
  구축목적 수립 &gt; 사전학습 모델구축 &gt;  sLLM 평가 &gt;  sLLM 배포
기술요소 프파작모 오디증합
  모델측면
    Pre-Trained - 사전 학습된 모델 기반 감독학습
    Fine tuning - 사전 학습 모델 기반으로 미세 조정을 통해 Task 맞춤형 모델 개발
    작은 모델크기 - LLM 모델 대비 적은 파라미터 수
    모델 경량화 - 엣지 컴퓨팅과 같은 제한된 리소스 환경에서도 사용 가능
  데이터측면
    Distillation Data - 모델을 효과적으로 개선하고 새로운 환경에 적용가능한 기술
    Open-source Data - 모델과 데이터가 오픈 소스로 제공
    데이터 증강 - 데이터 양이 제한적으로 기존 데이터를 다양하게 활용
    합성데이터
한계, 대응전략
  기술적측면
    성능제한 - 모텔 크기와 성능의 트레이드 오프 고려
    Fine tuning 한계 - fine tuning에 더 많은 시간과 노력을 통해 조절
  비즈니스측면
    전문성 부족 - 추가 도메인 지식 통합, 특화 모델과 함께 사용
    AI 할루시네이션 - 검색엔진 연동 데이터 수집
- 로컬 LLM

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
