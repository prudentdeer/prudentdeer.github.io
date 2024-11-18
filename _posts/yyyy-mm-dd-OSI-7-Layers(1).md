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
      I. 구분 전송단위 프로토콜 특징 게라브리 세페프비
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. OSI 7 Layers의 정의
        </div>
        <div class="para-cntnt">
            특징 - 응용 프로그램간 정보교환 / 사용자 인터페이스 / 전자우편 / 데이터베이스관리 등 서비스
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
            PDU - Data
  장비 - L7 스위치
  프로토콜 - HTTP, SMTP, FTP, TELNET
Presentation 
  특징 - 프로그램 간 데이터 표현 차이 해소 / 정보압축 / 해제 / 암복호화 / 제어코드 / 문자, 확장자
  PDU - Data
  장비 - 
  프로토콜 - MIME, SSL, ASCII
Session 
  특징 - 프로그램간 논리적 연결 확립, 유지, 중단 / 데이터 송수신 위한 설정, 동기화 / 포트 연결
  PDU - Data
  장비 - 
  프로토콜 - NetBIOS, RPC, WinSock
Transport 
  특징 - 패킷조합 / 시퀀싱 / 분해 / 흐름제어, 오류 검출 / 신뢰성연결 / 패킷 전송 제어
  PDU - Segment
  장비 - 게이트웨이, L4 스위치
  프로토콜 - TCP, UDP, SCTP
Network 
  특징 - 노드간 패킷 전송 / 주소부여(IP) / 논리적인 통신라우팅
  PDU - Packet
  장비 - 라우터, L3 스위치
  프로토콜 - IP, ARP, ICMP, IGMP
DataLink 
  특징 - 프레임 주소부여 / 에러검출 / 재전송 / 흐름제어
  PDU - Frame 
  장비 - 브리지, L2 스위치
  프로토콜 - 이더넷, HDLC, PPP, FEC, BEC
Physical 
  특징 - 섬유, 동축케이블 / 장치들의 전기적, 물리적 세부사항 정의  
  PDU - Bit
  장비 - 허브, 리피터, 네트워크 카드(NIC)
  프로토콜 - X.21, RS-232

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
