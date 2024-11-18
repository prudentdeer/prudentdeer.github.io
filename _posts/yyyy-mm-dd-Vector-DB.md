---
title: Vector DB
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
      I. 벡터 데이터베이스
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Vector DB의 정의
        </div>
        <div class="para-cntnt">
            고차원 데이터를 벡터 형태로 임베딩 하여 저장하고 쿼리하기 위해 특화된 데이터베이스
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Vector DB
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Vector DB의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Vector-DB.png" alt="Vector DB">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Vector DB의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 색조후 해양임코유프결
  색인
    해싱 - 빠른 결과를 제공하고 대략적인 결과를 생성
    양자화 - 벡터를 더 작은 부분으로 나누고 코드로 표현한 다음 다시 병합
    임베딩 - TF-IDF, CBOW, Skip-gram, Word2Vec
  조회
    코사인유사도 - 벡터 공간에서 두 벡터 사이의 각도의 코사인 측정
    유클리드거리 - 벡터 사이의 직선 거리를 측정
  후처리
    프롬프트 엔지니어링 – 생성형 AI 입력 프롬프트 설계 및 제작
    결과 추출 및 시각화 – 결과 추출 데이터의 시각화 도구 연계
LLM 적용방안 할장
  할루시네이션 - 검색된 정보기반 답변생성
  장기기억문제 - 벡터데이터베이스 기록저장

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
