---
title: OpenFlow
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
      I. 네트워크 장비의 표준 인터페이스 기술, OpenFlow의 개요
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. OpenFlow의 정의
        </div>
        <div class="para-cntnt">
            SDN 환경에서 제어 계층과 데이터 계층 사이 컨트롤러와 디바이스 통신 정의하는 기술 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. OpenFlow
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. OpenFlow의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/OpenFlow.png" alt="OpenFlow">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. OpenFlow의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 컨 프채그플파
  Controller 
    Controller - OpenFlow 프로토콜에 의해 스위치 내부의 플로우 테이블 작성
  OpenFlow Switch
    프로토콜 - 스위치와 컨트롤러 통신 인터페이스
    Channel - 스위치와 컨트롤러 사이 명령 및 패킷 암호화
    Group Table - 다수 플로우 테이블 포트를 하나의 그룹으로 추상화
    Flow table - 플로우 테이블 항목(필드, 카운터, 패킷 매칭 명령집합 등)과 동작을 연결하여 각패킷 룩업과 포워딩
    Pipeline - 각 플로우 테이블의 패킷 프로세싱 통로

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
