---
title: OSI 7 Layers
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
      I. Dejure 표준화 모델, OSI 7 Layer
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. OSI 7 Layers의 정의
        </div>
        <div class="para-cntnt">
            네트워크 통신에서 생기는 충돌 문제를 완화하기 위해 표준화한 ISO 7498 네트워크 모델
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. OSI 7 Layers
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. OSI 7 Layers의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/OSI-7-Layers.png" alt="OSI 7 Layers">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. OSI 7 Layers의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          계층설명 아파서티내다피
  7 - Application - 사용자 네트워크 접근할 수 있도록 하는 계층
  6 - Presentation - 운영체제의 부분으로 I/O 데이터 표현형태 변환
  5 - Session - 통신세션 구성계층, 포트연결 확인과 상호작용 설정
  4 - Transport - 메시지를 발신지 대 목적지간 제어와 에러관리
  3 - Network - 여러개의 노드를 거칠때마다 경로를 찾아주는 역할
  2 - Data Link - 포인트 투 포인트간 신뢰성있는 전송을 보장하기 위한 계층
  1 - Physical - 물리적 매체를 통해 비트의 흐름 전송, 물리접속
특징 캡서다페
  계층역할
    캡슐화, 프로토콜 사용 - 계층 간 역할 정의
    서비스 프리미티브 - 상위, 계층의 서비스 요구, 지시, 응답, 확인 통한 계층간 통신기능
  통신역할
    페이로드 전송 - APP 간 메세지 교환
    다중화, 역다중화 - 포트 기반 세그먼트화
OSI 7 Layer 와 TCP/IP 비교
  목적 - 모델 표준 제시 &lt;&gt; 네트워크 통신 구현
  계층 - 7계층 &lt;&gt; 4계층
  속성 - 표준 참조 모델 &lt;&gt; 프로토콜 규약
  특성 - 정형성, 규칙성 &lt;&gt; 유연성(연결/비 연결)
  표준 - De Jure Standard (법률표준) &lt;&gt; De Facto Standard (사실표준)

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
