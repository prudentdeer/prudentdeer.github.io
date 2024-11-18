---
title: 센서 라우팅
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 네트워크]
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
      I. 센서 라우팅
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 센서 라우팅의 정의
        </div>
        <div class="para-cntnt">
            센서네트워크에서 센서노드가 주변환경 측정 데이터정보를 주기적, 실시간 싱크 전송하는 라우팅
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 센서 라우팅
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 센서 라우팅의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/센서-라우팅.png" alt="센서 라우팅">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 센서 라우팅의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형
  평면 라우팅
    Directed Diffusion - Query Broadcasting에 기반 라우팅
    SPIN - 센서 노드가 데이터에 대해 광고하고 싱크로부터 요청을 기다리는 형태 (Sensor Protocols for Information Negotiation)
    SAR -  QoS, 각 패킷의 우선순위 고려 (Sequential Assignment Routing)
  계층적 라우팅
    LEACH - 클러스터링 기반 라우팅 (Low-Energy Adaptive Clustering Hierarchy)
    TEEN - 시간 임계적인 데이터를 처리 (Thresholdsensitive Energy Efficient sensor Network Protocol)
    APTEEN - 사전적 센서네트워크와 반응적 센서네트워크 한계 최소화(Adaptive Periodic Thresholdsensitive Energy Efficient sensor Network Protocol)
  위치기반 라우팅
    GEAR (Geographic and Energy-Aware Routing)
    GAF (Geographic Adaptive Fidelity)
평면, 계층 라우팅 비교
  스케쥴링 - 경쟁기반 &lt;&gt; 예약기반
  충돌 - 오버헤드 존재 &lt;&gt; 충돌회피
  동기 - 없음 &lt;&gt; 전역, 지역 동기

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
