---
title: 사이버 디셉션 (Cyber Deception)
#author: 
date: 2024-01-19 00:00:10 +0800
categories: [PE, 보안]
published: true
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
      I. 허니팟의 진화, 사이버디셉션
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 사이버디셉션의 정의
        </div>
        <div class="para-cntnt">
            공격자를 가짜함정으로 유도, 내부보안 방어 및 실시간 탐지 모니터링 가능한 공격자 기만 보안기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 사이버디셉션
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 사이버디셉션의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/사이버디셉션.png" alt="사이버디셉션">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 사이버디셉션의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 디트시 루페네오
  Decoy(미끼)
    루어토큰 - 공격자를 유인하는 가짜 인증토큰
    페이크드라이브 - 공격자 유인하는 가짜 저장소
  Trap(함정)
    NW - 가상 유도 NW, 트래픽 생성, Access Control, 이메일 정보
    EndPoint - 에이전트 정보, 방화벽, 경로별 정보 유도, USB, 포트
    OS - Root 정보, 사용자 인증, 접근제어 허가, 메모리 유도
  System
    NW 탐지 - 이상접근, 미끼기반 모니터링, 랜섬웨어 확인, 현상파악
    포렌식 - 정당성 확보를 위한 근거 추출, 이상현상에 대한 원인 분석
    User Interface - 실시간 트래픽 모니터링, 포트 등 다경로 시각화 수행/제공
사이버디셉션과 허니팟 비교
  대응범위 - 내/외부 접근 &lt;&gt; 외부접근
  라이선스 - 라이선스 최소화 &lt;&gt; 가상화 등 많은 라이선스 필요
  오탐율 - 오탐율 최소화(제로화) &lt;&gt; 오탐지 높음
  탐지방식 - 포괄적 탐지(자동화 구현/확장) &lt;&gt; 로그분석 기반
  확장 - 포괄적 배치 &lt;&gt; 제한적 배치

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
