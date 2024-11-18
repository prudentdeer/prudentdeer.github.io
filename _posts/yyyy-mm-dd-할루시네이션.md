---
title: 할루시네이션
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
      I. 생성형 AI의 결함, 할루시네이션
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 할루시네이션의 정의
        </div>
        <div class="para-cntnt">
            생성형 AI 에서 발생하는 현상으로, 훈련 데이터에 없는, 혹은 잘못된 정보를 생성하는 현상
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 할루시네이션
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 할루시네이션의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/할루시네이션.png" alt="할루시네이션">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 할루시네이션의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 내 외
  내재적 환각 - 소스 컨텐츠와 모순되는 출력을 생성하는 유형
  외재적 환각 - 소스 컨텐츠에서 확인할 수 없는 출력을 생성하는 유형
원인 불프과적
  불충분한 데이터 - 편향되거나 데이터 부족으로 제한된 이해를 바탕으로 학습
  프롬프트 부정확 - 은닉층 및 하이퍼 파라미터의 복잡성으로 인한 감수성 오류
  과적합 모델 - 훈련 데이터가 아닌 신규 데이터에 대한 비일반화 출력
  적대적 공격 - 악의적 공격을 위한 프롬프트 엔지니어링 기법 기반 조작
대응 검응알설
  RAG 검색증강 - 구글, bing 연동 통해 사실정보 수집
  응답길이제한 - 모델의 출력에 제약을 도입
  RLHF - 인간의 피드백을 통합하여 오류나 잘못된 정보를 표시하고 수정
  설명가능한 AI - 어떤 데이터에서 문제가 시작됐는지를 파악
- Confabulation(작화증) 이라고 해야 한다는 논쟁이 진행
https://www.skelterlabs.com/blog/bellaqna-rag-hallucination

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
