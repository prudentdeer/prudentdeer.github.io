---
title: ELK Stack
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
      I. Realtime 분석, ELK stack
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ELK Stack의 정의
        </div>
        <div class="para-cntnt">
            Elastic search, Logstash, Kibana 조합 실시간 로그분석, 시각화제공 오픈소스 스택
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. ELK Stack
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ELK Stack의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/ELK-Stack.png" alt="ELK Stack">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. ELK Stack의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 비로엘키
  Beats
    엣지로그 수집 - 엣지단 동작 경량수집기, Logstash로 전송
  Logstash
    파이프라인 - 로그수집, 필터링, 정제
    인덱싱 최적화 - 배치처리, 병렬처리 통한 인덱싱성능 최적화
  Elastic search
    Lucene 기반 - 스코어링, 연관도정렬, 최적 자료구조
    DSL - 반정규화 기본 모델링 (Domain Specific Language)
  Kibana
    대시보드 - 다양한 시각화 도구를 통해 데이터를 그래픽으로 시각화
    SIEM - 보안 이벤트 관제 가능
ELK 와 Grafana Loki 비교
  풀텍스트검색 - 빠름 &lt;&gt; 느림
  로그보관기간 - 제한 &lt;&gt; 장기간
  스케일링 - 어려움 &lt;&gt; 유연함
  레퍼런스 - 많음 &lt;&gt; 적음
- 하둡, 카프카, RDB 연동, 빅데이터 파이프라인 일부로 동작

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
