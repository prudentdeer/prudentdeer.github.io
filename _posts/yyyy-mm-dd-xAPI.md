---
title: xAPI
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 디지털서비스]
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
      I. 학습경험 데이터수집 표준 xAPI
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. xAPI의 정의
        </div>
        <div class="para-cntnt">
            분산학습환경의 비정형 학습데이터 수집위해 학습경험 트리플모델 구성 LRS 저장 기술표준
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. xAPI
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. xAPI의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/xAPI.png" alt="xAPI">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. xAPI의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          대시보드, 개인화서비스, LMS
구성요소 아보클스
  트리플모델
    Actor - 학습자/학습활동 참여개체 
    Verb - 학습활동 유형 설명 
    Object - 학습활동의 대상 
  저장구조
    Context - 상황정보
    Result - 측정결과 
    LRS - 학습데이터 저장/공유 시스템
    Statement - 학습활동 세부정보 저장형태
xAPI 와 Caliper Analytics 비교
  보안 - OAuth &lt;&gt; API key
  전송방식 - JSON &lt;&gt; JSON-LD
  라이센스 - Apache2 &lt;&gt; 회원사 제한
- 두 방식 모두 LRS 저장목적, 세부방식 차이점, Learning Record Store

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
