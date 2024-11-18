---
title: RAG
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
      I. 할루시네이션 극복. 검색증강 생성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. RAG의 정의
        </div>
        <div class="para-cntnt">
            생성형 AI 이용시 검색엔진연동, 벡터DB 활용하여 정확성과 신뢰성을 향상시키는 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. RAG
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. RAG의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/RAG.png" alt="RAG">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. RAG의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          기술요소 문입정답출
  문서저장 / Embedding, Vector DB - 임베딩하고 Indexing하여 Vector DB에 저장
  입력쿼리 / Query, Chunk 분할 - 입력 쿼리를 검색 시스템이 이해할 수 있도록 쿼리 처리
  정보증강 / Context, 증강입력 - 증강된 입력이 형성되며, 쿼리와 검색된 문서의 추가 맥락포함
  답변생성 / Seq to Seq - 언어 모델은 입력된 내용을 처리하고 응답을 생성
  출력생성 / 정제, 형식화 - 최종 응답을 RAG 프로세스의 출력으로 전달
RAG, HITL 비교
  개념 - 환각억제 &lt;&gt; 편향감소
  적용 - 외부데이터 &lt;&gt; 사람피드백
  적용 - 생성 AI &lt;&gt; 기계학습

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
