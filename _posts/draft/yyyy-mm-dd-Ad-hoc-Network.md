---
title: Ad-hoc Network
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
      I. 노드 이동성 보완, Ad-hoc 라우팅
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Ad-hoc Network의 정의
        </div>
        <div class="para-cntnt">
            통신 인프라가 없는 상황에서, Node 간 자율적인 경로설정, 의사소통 가능한 라우팅 프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Ad-hoc Network
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Ad-hoc Network의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Ad-hoc-Network.png" alt="Ad-hoc Network">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Ad-hoc Network의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징 (구조/통신) 이동불피
  이동노드 - 호스트 이자 ad-hoc 라우팅 기능 가짐
  동적 토폴로지 - 일부 또는 전체가 나타나거나 사라짐
  불안전 링크- 전송 거리, 대역폭에 제한과 전파 간섭 및 다중 링크로 인한 보안 문제
  P2P 통신 - 무선 인터페이스를 사용해 이동 노드들 간에 통신
유형
  Proactive - 모든노드 주기적 라우팅 Broadcasting, 자신 라우팅 변경시 다른노드 전파 프로토콜
    특징 - Broadcasting, 최신정보 유지, 즉시연결
    장점 - 경로설정시 경로획득절차 불필요, 낮은 지연율
    단점 - 라우팅 정보 유지 메시지로 오버헤드 증가
    활용 - 소형 Ad-hoc 네트워크에 적합
    유형 DW
      DSDV - Sequence Number 통해 최신 메시지 판단 / Destination Sequenced Distance Vector
      WRP - 메시지 재전송 리스트 테이블 기반 정보 송/수신 / Wireless Routing Protocol
      CGSR
  Reactive - 라우팅 정보 Broadcasting 하지않고, 필요시 Ondemand 경로설정 수행 프로토콜
    특징 - On-demand, 최신정보 아님, 정보갱신 후 연결
    장점 - 라우팅 정보 유지 필요없어 오버헤드 적음
    단점 - 경로 설정시 전체 망 검색으로 지연발생, 낮은속도
    활용 - 위치이동이 많은 Ad-hoc Network 적합
    유형 DA
      DSR - 경로발견, 경로유지 메커니즘 기반 구성 / Dynamic Source Routing
      AODV - 라우팅 경로 발견 시, 이웃 노드에 브로드캐스팅 / Ad Hoc On-demand Distance Vector
      TORA
  Hybrid
      ZRP : 동일영역 Proactive, 외부영역 Reactive / Zone Routing Protocol
Proactive 와 Reactive 비교
  경로유지 - Boradcasting &lt;&gt; On demand
  업데이트 - 주기적 &lt;&gt; 요청시
  대역폭사용 - 높음 &lt;&gt; 낮음
  초기지연 - 낮음 &lt;&gt; 높음
  라우팅테이블 - 큼 &lt;&gt; 작음

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
