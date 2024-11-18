---
title: 트랜스포머
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
      I. All You Need is Attention, 트랜스포머
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 트랜스포머의 정의
        </div>
        <div class="para-cntnt">
            RNN계열 알고리즘 사용없이 셀프어텐션 기반 인코더, 디코더 사용하는 자연어처리 모델
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 트랜스포머
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 트랜스포머의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/트랜스포머.png" alt="트랜스포머">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 트랜스포머의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 포인피 포마인피 선소
  인코더
    포지셔널 인코딩 - 입력단어의 위치 값 추가
    인코더 셀프어텐션 - 소스 언어의 단어 별 계산
    피드포워드 신경망 - Position-Wise 완전 연결망, 잔차(Residual) 연결이용 및 정규화 수행
  디코더
    포지셔널 인코딩 - 입력단어의 위치 값 추가
    마스크드 셀프어텐션 - 타겟 언어의 단어 별 계산
    인코더-디코더 어텐션 - 소스언어를 키로, 타겟언어를 쿼리로 하여 어탠션 연산
    피드포워드 신경망 - 인코더 구조와 동일
  출력
    선형레이어 - 디코더 출력을 벡터화하여 신경망 연결
    소프트맥스 - 출력단어 예측
트랜스포머를 활용한 모델 티비버지
  T5 - 텍스트를 텍스트로 변환 자연어 처리
  ViT - 비전 태스크에서 트랜스포머 어텐션 사용
  BERT - 자연어 이해와 처리를 위한 사전 훈련된 모델
  GPT - 텍스트 생성을 위한 트랜스포머 어텐션을 활용한 모델
https://www.aitimes.com/news/articleView.html?idxno=137202

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
