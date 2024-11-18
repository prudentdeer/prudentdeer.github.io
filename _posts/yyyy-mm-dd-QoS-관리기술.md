---
title: QoS 관리기술
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
      I. QoS 의 관리기술 모큐티티
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. QoS 관리기술의 정의
        </div>
        <div class="para-cntnt">
          수행모델 인디엠씨
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. QoS 관리기술
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. QoS 관리기술의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/QoS-관리기술.png" alt="QoS 관리기술">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. QoS 관리기술의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            IntServ – 흐름기반 트래픽의 QoS 보장 모델 (Integrated Service)
  DiffServ – 서비스 등급에 따른 QoS 보장 모델 (Differentiat ed Service) 
  MPLS – IP 헤더 이용 대신, 4Byte, Label 참조, 고속 2계층 포워딩 처리기술 (Multi Protocol Labeling Switch) 
  CDN – 컨텐츠 캐싱을 통한 빠른 서 비스 제공 기술 (Content Delivery NW) 

Queueing 피프클커웨클
  FIFO Queuing : 먼저 들어온 패킷이 먼저 나간다는 스케줄링
  PQ, Priority Queuing : “High, Medium, Normal, Low” 4가지 클래스로 나눠 차등화된 서비스
  CBQ, Class Based Queuing : 서비스 클래스에 따라 서비스 큐를 정의, Starvation을 방지
  CQ, Custom Queuing : 각 클래스 별 큐를 Round-Robin방식으로 하나씩 돌아가면서 처리
  WFQ, Weighted Fair Queuing : 가중치
  CBWFQ, Class-Base Weight Fair Queuing : 각 클래스 마다 Bandwidth, Weight, Packet Limit 정책을 정의   

Traffic Shaping 쉐토리하 
  - 버퍼를 사용하여 목표속도 이상 들어오는 트래픽을 잠시 저장 후 서비스 
  Token Bucket (속도제어) : 토큰 형태 Credit 축적, Token 유무 따른 흐름제어, RFC 2697/2698 정의 버킷(Bucket) 사용   
  Leaky Bucket (용량제어) : 인입 트래픽 버킷에 저장, 버킷 속도 평준화, 버킷 과도 시 폐기, 트래픽 성형 기술의 대표적 알고리즘 
  Hybrid Bucket (속도용량)

Traffic Policing 포레가테
  - 기준이상 초과트래픽 버림으로 대역폭 제한 
  RED - 혼잡사항 사전감지 Drop (Random Early Detection)
  WRED - 패킷 가중치에 따라 Drop (Weighted Random Early Detection)
  Tail Drop - 버퍼 임계치 초과시 모두 Drop

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
