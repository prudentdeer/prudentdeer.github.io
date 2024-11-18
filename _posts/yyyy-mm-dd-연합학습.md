---
title: 연합학습
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
      I. 탈중앙화 학습, 연합학습
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 연합학습의 정의
        </div>
        <div class="para-cntnt">
            데이터 보안을 위해 로컬모델 집계해 글로벌모델 업데이트하는 탈중앙화 기계학습 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 연합학습
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 연합학습의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/연합학습.png" alt="연합학습">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 연합학습의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          등장배경
  분산데이터급증 / 프라이버시 / 환경다양화
절차 분갱취갱
  전역모델 분배 - 각 단말로 수행해야 할 작업 관련 정보를 전달
  지역모델 갱신 - 개인 데이터를 사용하여 로컬 AI 모델을 생성
  지역모델 취합 - 생성한 로컬 AI 모델의 결과값(파라미터)을 압축・암호화하여 서버로 전달
  전역모델 갱신 - 취합된 값을 이용하여 전역 모델을 갱신
알고리즘 다쓰 (명)박이꺼
  평균기반
    FedDyn / 동적정규화 - 수정된 손실이 글로벌 손실 반영
    FedAVG / 평균기반 - 로컬 모델의 평균 업데이트
    FedSGD / 경사하강법 - 확률적 경사 하강법 학습
    FedSparse / 희소성유지 - 로컬 업데이트 중앙 평균화
  변형기반
    FedPara / 매개변수 - 매개변수의 수를 변경 (re-Parameterization for FL)
    FedAda / 동적학습률 - 학습률을 동적으로 조절
    FedGiA / 연산비용감소 - 약한 가정 내에서수렴 (FL via GDand inexact ADMM) 
    FedGAN / 적대신경망 - 가짜 데이터를 중앙 서버로 전송 
프라이버시 보호 기술 차동다
  차등정보보호 - 데이터에 수학적 노이즈를 추가하여 프라이버시 노출 위험 감소
    Perturbation - 원자료에 노이즈 추가 교란
    Local 차등보호 - 자료수집단계 직접 정보보호처리 
  동형암호 - 암호화된 데이터를 복호화 없이도 연산할 수 있는 암호기술
    부분, 준동형, 완전동형암호
  다자간 계산 - 각자의 비밀 값을 입력값으로 하여 함숫값을 함께 계산하는 기술
    Secure Aggregation - 총계기법에 보안성 강화
연합학습과 분산학습 비교
  목적 - 정보, 데이터보호 &lt;&gt; 성능향상
  인프라 - 여러 기기, 기업 &lt;&gt; 하나의 클러스터
  데이터 - 로컬분산 &lt;&gt; 중앙관리
  통신 - hub and spoke &lt;&gt; 분산형
  프라이버시 - 보장 &lt;&gt; 미보장
- 연합학습은 직접 데이터를 주고받지않아 프라이버시를 보장

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
