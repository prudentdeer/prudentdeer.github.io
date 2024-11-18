---
title: ARP 스푸핑
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
      I. 스위칭 환경의 MITM, ARP Spoofing
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ARP 스푸핑의 정의
        </div>
        <div class="para-cntnt">
            MAC주소를 동일 네트워크에 존재하는 다른 PC주소로 위장, 정보를 가로채는 MITM 공격방식
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. ARP 스푸핑
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ARP 스푸핑의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/ARP-스푸핑.png" alt="ARP 스푸핑">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. ARP 스푸핑의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          공격탐지
  ARP Table조회를 통한 MAC 주소 중복 확인
  송신패킷에서 악성코드 유무 검사
  비정상 ARP 패킷수신 확인
  ARP Table 감시도구 활용
  ARP Spoofing 실행 프로그램 확인
  네트워크 어댑터의 동작상태 확인
  ARP 패킷 관찰
대응방안
  인증요소 추가
  보안수준 강화
  Static ARP 관리
  MAC Flooding 관리
  패킷 모니터링
  암호화

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
