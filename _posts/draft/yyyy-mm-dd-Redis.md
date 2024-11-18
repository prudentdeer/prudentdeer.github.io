---
title: Redis
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
      I. 인메모리 NOSQL, Redis
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Redis의 정의
        </div>
        <div class="para-cntnt">
            분산환경 비정형 데이터 저장, 관리위해 Key-Value 구조기반 오픈소스 인메모리 NOSQL DBMS
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Redis
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Redis의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Redis.png" alt="Redis">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Redis의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 마슬레센스
  마스터 - 데이터 복제와 Slave 서버 관리
  슬레이브 - 주로 읽기 요청을 처리하는 서버
  레플리카 - Master 서버에 쓰인 내용을 복제
  센티넬 - Master 서버의 HA 기능 제공
  스냅샷 - 특정 간격으로 디스크에 백업 기록
Redis 와 Kafka 비교
  브로커타입 - 메시지 브로커 &lt;&gt; 이벤트 브로커 
  데이터저장 - 인메모리 DB &lt;&gt; 디스크 기록
  데이터형식 - 키, 값 구조 &lt;&gt; 이벤트 스트림
  중복구독 - 한 메시지를 다수의 Subscriber가 구독 &lt;&gt; 한 이벤트는 하나의 Subscriber 만 구독
  데이터유실위험 - 있음 &lt;&gt; 없음
  구독형태 - Push &lt;&gt; Pull 
  처리속도 - 빠름 &lt;&gt; 상대적 느림
  취급규모 - 저용량 데이터 &lt;&gt; 대용량 데이터

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
