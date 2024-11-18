---
title: HTTP 3.0
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
      I. 차세대 웹 프로토콜, HTTP 3.0의 개요
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. HTTP 3.0의 정의
        </div>
        <div class="para-cntnt">
            HOLB 문제 해결위해 QUIC, 0-RTT, Multistream 이용 UDP 기반 RFC 9114 프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. HTTP 3.0
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. HTTP 3.0의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/HTTP-3.0.png" alt="HTTP 3.0">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. HTTP 3.0의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            Head Of Line Blocking - 같은 큐에 있는 패킷이 첫번째 패킷에 의해 지연될때 발생하는 성능저하
구성요소 삼큐티유 012
  핵심
    HTTP/3 - HTTP 3.0의 신규 헤더 구성
    QUIC - HOL 블로킹 해결, RTT 최소화, 멀티 스트림 제공 
    TLS 1.3 - 암호화를 통한 단순성, 속도 개선
    UDP - 비연결지향, 데이터그램 이용, 1회의 Hand Shake
  핸드쉐이크
    0-RTT - 이전에 연결한 적이 있는 서버에 재접속
    1-RTT - QUIC의 기본 연결 설정 방식
    2-RTT - 기존 TCP와 유사한 방식으로 연결설정을 수행
HTTP 2.0과 3.0의 비교
  프로토콜 - TCP 기반 &lt;&gt; UDP 기반 (QUIC)
  핸드쉐이크 - 3-WAY 핸드쉐이크 &lt;&gt; 0-RTT 핸드쉐이크
  헤더 압축 - HPACK &lt;&gt; QPACK
  보안 - TLS 1.2, 1.3 &lt;&gt; TLS 1.3

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
