---
title: 머신러닝파이프라인
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
      I. 머신러닝의 순차적인 흐름, 머신러닝 파이프라인
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 머신러닝파이프라인의 정의
        </div>
        <div class="para-cntnt">
            데이터 수집에서 예측 제공 단계까지의 전 과정을 순차적으로 처리하는 머신러닝의 아키텍처
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 머신러닝파이프라인
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 머신러닝파이프라인의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/머신러닝파이프라인.png" alt="머신러닝파이프라인">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 머신러닝파이프라인의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          단계별 설명 수준모예
  데이터수집
    Data Lake - 정기적 업데이트 라이브 데이터
    ETL - 다운로드된 동결된 데이터 집합
  데이터준비
    Normalization - 데이터 소스를 교육에 사용할 수 있는 일관성 확보
    Bias Analysis - 모델에 포함된 편견 제거
  모델학습
    Hyper Parameterization - 정확도 향상위해 학습을 튜닝
    Parallelization - 병렬성 활용해 작업분산하여 성능 향상
  예측제공
    예측제공 - 학습 모델배치하여 서비스 제공하는 단계
    재학습
파이프라인 이점 무재추
  무인실행 - 안정적 방식 병렬실행, 순차실행 가능
  재사용 가능 - 재학습, 특정 시나리오 파이프라인 템플릿 이용가능
  추적 및 버전관리 - 파이프라인 SDK 사용하여 버전관리 가능 

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
