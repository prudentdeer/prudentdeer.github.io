---
title: DoS, DDoS
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 보안]
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
      I. 분산 서비스거부 공격, DDoS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DoS, DDoS의 정의
        </div>
        <div class="para-cntnt">
            대량의 Agent 통해 네트워크, 시스템의 자원을 고갈하여 DOS 유발 시키는 분산 서비스 거부공격
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DoS, DDoS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DoS, DDoS의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DoS,-DDoS.png" alt="DoS, DDoS">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DoS, DDoS의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          공격유형 대자부 / UI SD GS
  대역폭 소진공격 
    UDP Flooding - 출발지 IP를 위변조, UDP 프로토콜 패킷 전송
    ICMP Flooding - ICMP Request 이용, 대량의 패킷 생성후 전송
  자원소모 공격
    Syn Flooding - TCP 프로토콜 3way-handshake 이용, ACK 안하고 SYN 전송
    DNS Query Flooding - DNS 서버에 대량 질의, 피해서버 트래픽폭주 유발
  부하유발 공격
    Get Flooding - TCP 프로토콜 이용, Get요청으로 서버자원소진
    Slowloris - HTTP 헤더 변조, 연결유지로 서버자원 잠식
기술적 대응방안 대자부 / 차필 임비 세시
  대역폭 소진공격
    차단 - 라우터, 방화벽에서 ICMP 프로토콜 차단
    필터링 - ISP 인터페이스 설정, ACL 필터링 적용
  자원소모 공격
    임계치 설정 - PPS 임계치 설정 후 정책의 적용
    비정상 패킷검출 - 패킷의 헤더검사, 비정상적 패킷 차단
  부하유발 공격
    세션 타임아웃 - WAS 의 세션 타임아웃 설정
    시그니처 등록 - HTTP 헤더표준검사, 시그니처 등록 차단
관리적 대응방안 보백사이
  내부
    보안조직 - 보안 전담조직의 신설
    백업구축 - DDOS 공격 피해 최소화 및 우회 서비스
  외부
    사이버대피소 - KISA의 사이버대피소
    ISP 업체 연계 - 서비스 앞단의 1차적 방어선 마련
- 사이버대피소, 스크러빙센터, 리버스프록시

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
