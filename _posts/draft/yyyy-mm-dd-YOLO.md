---
title: YOLO
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
      I. Unified Detecting, YOLO
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. YOLO의 정의
        </div>
        <div class="para-cntnt">
            빠른 속도 객체탐색 위해 Bounding box, 클래스확률맵 이용 객체 탐색 및 분류 알고리즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. YOLO
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. YOLO의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/YOLO.png" alt="YOLO">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. YOLO의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          프로세스 스바클객
  S x S 그리드 / 셀 분할 - 해당 셀에 물체의 중심이 있는지 판단
  바운딩 박스 / 신뢰도 측정 - 모델이 박스안에 물체가 어느 정도 있는지 판단하는 지와 정확도를 표시
  클래스 확률맵 / 확률예측 - 해당 셀에 물체가 있을 때 어떤 클래스가 있을지 조건부 확률을 계산
  객체 인식 / CNN Network - GoogleLeNet, VGGNet 등 CNN Network 이용 객체 분류
주요기술 그바다 씨컨클
  객체탐색 기술
    Grid - Image를 S x S 격자로 구성, 인접 grid기반 객체 인식
    Bounding Box - 객체 경계 결정 알고리즘, x, y, w, h, Confidence Score
    Darknet - 신경망 프레임워크, CUDA, OpenCV 영상처리
  객체분류 기술
    CNN - Convolutional Layer, Pooling, Connected Layer
    Confidence Score - 각 B-Box Grid cell 신뢰수치
    Class Probability - Loss 기법 기반 분류 예측
개인정보보호 측면 고려사항 비분개피
  저장측면
    비식별조치 - 얼굴데이터 비식별 가공
    분산저장 - 민감정보 분산저장
  활용측면
    개인정보보호법 준수 - 정보주체의 동의 필수
    PET 기술적용 - 개인정보 강화기술 적용

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
