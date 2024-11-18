---
title: 성능 테스트
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 소프트웨어공학]
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
      I. 리틀의법칙 기반, 성능 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 성능 테스트의 정의
        </div>
        <div class="para-cntnt">
            요구사항에 부합하는 SW의 처리능력 검증위해 정량적, 정성적 성능지표 이용한 테스트
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 성능 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 성능 테스트의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/성능-테스트.png" alt="성능 테스트">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 성능 테스트의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          지표 효신가내 티쓰응자
  정성적 - 효율성 / 신뢰성 / 가용성 / 내구성
  정량적 - TPS / Throughput / 응답시간 / 자원사용량
절차 요계설구 수종
유형
  대상 단복임
    단위성능 테스트 - 대상 시스템을 업무 단위로 각각 테스트 
    복합성능 테스트 - 동시 사용자 및 가중치를 통해 상황을 재현하여 테스트
    임계성능 테스트 - 시스템이 최대 발휘할 수 있는 성능 측정
  기법 로스티확가
    Load Test - 부하를 주고 이상을 파악하는 시험
    Spike Test - 순간적으로 transaction을 증가하여 시험
    Tier Test - 성능 병목 구간을 찾기 위한 시험
    확장성 테스트 - 증설에 대한 성능 향상 비율 측정
    가용성 테스트 - 정상적인 시스템 동작에 대한 테스트
- 리틀의 법칙에 의해, Saturation Point 가 넘어가면 응답시간 지연
- TPS 
    = AU / MRT
    = CU / RI (Request Interval Time)
  RI = Response + Think time

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
