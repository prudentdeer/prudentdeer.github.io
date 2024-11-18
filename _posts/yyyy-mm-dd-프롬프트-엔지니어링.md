---
title: 프롬프트 엔지니어링
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
      I. LLM 모델의 성능 극대화 위한, 프롬프트 엔지니어링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 프롬프트 엔지니어링의 정의
        </div>
        <div class="para-cntnt">
            LLM에서 원하는 결과 얻기위해 품질을 높일 수 있는 프롬프트 입력값들의 조합을 찾는 작업
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 프롬프트 엔지니어링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 프롬프트 엔지니어링의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/프롬프트-엔지니어링.png" alt="프롬프트 엔지니어링">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 프롬프트 엔지니어링의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 명맥페예 포어
  필수요소
    명령 - 특정 태스크 또는 지시사항
  개선요소
    맥락정보 - 어떤 배경인지, 어떤 조건이나 규칙이 있는지, 최종적으로 어떤 결과물인지
    페르소나 - 가상 답변인물 지정
    예시 - 문제와 관련된 예시를 1~2개
  부가요소
    포맷 - 결과물의 형식이나 분량, 내용 구성
    어조 - 간단명료하게, 친근한 말투로
프롬프팅 기법 제원퓨
  제로샷 프롬프팅 - 예시를 제공하지 않고 간단한 명령어만 입력 (기사내용 3줄의 문장으로 요약)
  원샷 프롬프팅 - 하나의 예제 또는 템플릿 기반 답변 생성 프롬프트 기술
  퓨샷 프롬프팅 - 소량의 샘플 정보나 데이터 사용
- 할루시네이션 예방위해 RAG, 프롬프팅 중요

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
