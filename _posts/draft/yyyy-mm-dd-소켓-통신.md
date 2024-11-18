---
title: 소켓 통신
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
      I. 소켓통신
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 소켓 통신의 정의
        </div>
        <div class="para-cntnt">
            TCP/IP 기반 네트워크 소켓통해 Client-Server 간 특정 포트이용 양방향 연결지향 통신
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 소켓 통신
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 소켓 통신의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/소켓-통신.png" alt="소켓 통신">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 소켓 통신의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  서버-클라이언트 구조 - TCP/UDP 위에서 동작
  양방향 통신 - 양 쪽에서 실시간으로 데이터를 송수신
  언어, OS 종속성 - 운영체제, 언어마다 사용법이 다름
  프로토콜 독립성 - 다양한 네트워크 프로토콜을 사용
유형
  TCP Socket / 신뢰, 양방향 - 양방향 데이터 전송 가능하고, 실시간, 신뢰기반
  UDP Socket / 비신뢰, 단방향 - 단방향 데이터 전송, 재전송 없이 빠르게 전송
  Raw Socket / ICMP, 패킷교환 - 저수준 프로토콜 액세스
  Web Socket / HTML5, 실시간 - 지속적 연결유지, 웹서버와 웹브라우저 TCP 통해 전송
TCP 소켓흐름 소바리액센클
  socket() - 소켓생성
  bind() - ip와 Port 설정
  listen() - Client 접근요청 수신 대기열 요청
  accept() - Client와 연결대기
  send() recv() - 데이터 통신수행
  close()
Web 소켓흐름 해커비센원
  Handshake (HTTP upgrade)
  Connection opened
  Bi-directional message
  Send(), Onmessage()
  One side close channel
소켓통신과 HTTP 통신 비교
  방향성 - 양방향 &lt;&gt; 단방향
  프로토콜 - TCP,UDP 등 &lt;&gt; HTTP,HTTPS
  연결방식 - 직접연결 &lt;&gt; Request-Response 
  데이터형식 - Byte Stream or Message &lt;&gt; JSON,HTML,XML
  통신속도 - 빠름 &lt;&gt; 느림
  보안 - 방화벽, IDS, IPS &lt;&gt; HTTPS
  활용분야 - 스트리밍서비스 &lt;&gt; Web 서비스, Web Application, API 통신등

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
