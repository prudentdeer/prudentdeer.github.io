---
title: IPv6
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
      I. IPv4 한계 해소, IPv6
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IPv6의 정의
        </div>
        <div class="para-cntnt">
            IPv4 주소고갈 극복하기 위해 개발된 128비트 형태의 주소를 가진 차세대 인터넷 주소체계
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IPv6
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IPv6의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IPv6.png" alt="IPv6">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IPv6의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          IPv4의 문제점
  주소의 고갈 : 인터넷 이용자 폭증, 디지털 기기 IP 요구 증대
  기술상의 한계 : 이동식 네트워크의 오버헤드 발생
구성요소 버트플 파네홉 소디
  Version / 4 bit - IP Version 표시 (4 또는 6)
  Traffic Class / 8 bit - 송신장치에 송신 우선순위를 요청하는 기능
  Flow Label / 20 bit - QoS를 위한 서비스 별 구분 표시
  Payload Length / 16 bit - 데이터의 길이 표시
  Next Header / 8 bit - IP 헤더 다음에 나타나는 헤더의 유형을 정의
  Hop Limit / 8 bit - 패킷 전송 시 포워딩 제한 표시
  Source Address / 128 bit - 송신자 주소 표시
  Destination Address / 128 bit - 수신자 주소 표시
확장헤더
  Hop-by-Hop - 경로상의 모든 통신장비에서 패킷 처리시 필요한 정보
  Destination - 최종 목적지의 통신장비에서 패킷 처리시 필요한 정보
  Routing - 송신자에 의한 라우팅 경로 목록 정보
  Fragmentation - 전송길이 확대에 따른 패킷 분할 및 재조합 정보
  Authentication - 데이터 무결성 및 송신자 인증 정보
  Encapsulation Security - 패킷의 Payload 영역의 암호화

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
