---
title: ICMP
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
      I. ICMP, Internet Control Message Protocol
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ICMP의 정의
        </div>
        <div class="para-cntnt">
            네트워크의 상태 및 오류정보를 오류메시지, 질의어 통해 공유하는 통신 프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. ICMP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ICMP의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/ICMP.png" alt="ICMP">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. ICMP의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 타코체아오
  Type - ICMP 메시지 구분
  Code - 메시지 내용 자세한 정보
  Checksum - 전체 메시지에 대한 중보검사 기능
  IP헤더
  오류발생 패킷
메시지 유형
  오류보고 메시지 
    Destination unreachable - 라우터가 데이터그램을 라우팅할 수 없을 때
    Source quench  - 발신지 억제.  라우터나 목적지 호스트에서 혼잡으로 인해 데이터 그램이 폐기 
    Time exceeded - 라우터가 time to live 0인 데이터그램 받을 시  
    Parameter problem - 데이터그램의 헤더 부분에 불명료한 점이 있음 
    Redirection - 데이터그램을 재지정시 
  질의 메시지 
    Echo request or reply - 고장진단. 두 시스템이 서로 통신할 수 있는지 확인 
    Timestamp request and reply - IP데이터그램의 왕복 시간 결정 위한 time stamp 요청 및 응답 
    Address mark request and reply - 네트워크 주소와 서브넷 주소 식별 위한 주소 마스크 요청 및 응답 
    Router solicitation and advertisement - 라우터 주소 확인과 라우터 정상 동작 여부 확인
ICMP 와 IGMP 비교
  기능 - 오류보고, 문제해결 &lt;&gt; 그룹관리 
  특징 - 진단 도구로 활용, Ping 등 &lt;&gt; 트래픽 관리 
  메시지타입 - 오류보고, 질의 메시지 &lt;&gt; 그룹 가입, 유지, 탈퇴 
  패킷전송 - 유니캐스트, 브로드 캐스트 &lt;&gt; 멀티캐스트 
  전송방향 - 단, 양방향 &lt;&gt; 단방향
- TTL - Time To Live
  각, Router는 TTL 패킷이 날라올때 TTL Value를 1씩 감소시킨다
  TTL 값이 0이 되었을때는 라우터는 그것을 감지하여 해당 패킷을 버리고 ICMP 메세지를 발신지 host 에게 보내게 된다

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
