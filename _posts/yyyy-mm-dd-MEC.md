---
title: MEC
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
      I. 지연시간 최소화, MEC = 모바일 엣지 컴퓨팅
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MEC의 정의
        </div>
        <div class="para-cntnt">
            기존 클라우드 엣지컴퓨팅과 5G 망결합 통해 융합서비스 전송지연과 품질향상 컴퓨팅기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MEC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MEC의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MEC.png" alt="MEC">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MEC의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          필요성
  근접성 - 외부서버를 MEC 에 전진배치해 지연 최소화
  초저지연 - 5G망 이용시 지연 발생 최소화
  지역화 - 트래픽의 지역화 통해 대역폭 및 보안측면 효율화
기술요소
  EC 플랫폼
    MEC Host - 지역적으로 분산 설치된 공용 서버
    MEC Orchestrator - MEC 서비스, 응용, 플랫폼의 오케스트레이션 관리 
    MEC Platform Manager - MEC 서비스, 응용 및 구성요소의 수명주기 관리 
  MEC 연합 
    MEC 시스템 인증/허가 - 상대방 이동 통신사에 MEC 시스템에 대한 인증 및 허가 
    MEC 자원 정보 교환 - MEC 시스템 제공 기능 및 성능/용량, 네트워크, 컴퓨팅 자원 
    MEC 시그널링 - 사용자 단말 MEC 커버리지 이탈, MEC 시스템 발견 사용 
  MEC 네트워크 
    NEF - Network Exposure Function - QoS 정보 등을 개방하는 네트워크 인터페이스
    EASDF - EAS(Edge Application Server) Discovery Function - MEC 응용 서버 검색 및 연결을 위한 네트워크 기능 
    UPF - User-Plane Function - 데이터 유실 방지 패킷 버퍼링과 패킷 수신 IP 대체 기능 

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
