---
title: IGMP
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
      I. IGMP, Internet Group Management Protocol
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IGMP의 정의
        </div>
        <div class="para-cntnt">
            호스트가 멀티캐스트 그룹에 가입하거나 그룹에서 탈퇴하는데 사용되는 통신 프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IGMP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IGMP의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IGMP.png" alt="IGMP">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IGMP의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 타맥체그
  Type - 그룹질의, 보고, 탈퇴
  Max Response Time - 최대 응답 시간
  Checksum - 전체 메시지에 대한 중보검사 기능
  Group Address - 가입 원하는 그룹 주소  
메시지 유형
  Membership Query - 특정 그룹에 참여하는 호스트 있는지 확인조회
  Membership Report - 가입코자하는 그룹의 멀티캐스트 주소를 밝히는 것
  Leave Report - 더이상 특정 멀티캐스트 수신을 원하지 않음 
ICMP 와 IGMP 비교
  기능 - 오류보고, 문제해결 &lt;&gt; 그룹관리 
  특징 - 진단 도구로 활용, Ping 등 &lt;&gt; 트래픽 관리 
  메시지타입 - 오류보고, 질의 메시지 &lt;&gt; 그룹 가입, 유지, 탈퇴 
  패킷전송 - 유니캐스트, 브로드 캐스트 &lt;&gt; 멀티캐스트 
  전송방향 - 단, 양방향 &lt;&gt; 단방향
- PIM - 멀티캐스트 라우팅 트리를 구성할 수 있게하는 멀티캐스트 라우팅 프로토콜

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
