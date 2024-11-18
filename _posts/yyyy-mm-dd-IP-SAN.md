---
title: IP-SAN
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 컴퓨터구조]
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
      I. [정의] 기존 fiber channel로 이루어진 SAN과 Gbit 이더넷을 이용하는 IP 네트워킹 기술접목하여 운영, 성능의 효율성을 극대화한 기술
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IP-SAN의 정의
        </div>
        <div class="para-cntnt">
          상쇄), cost effective(별개 스토리지 전용 네트워크 구축 비용 증가)
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IP-SAN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IP-SAN의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IP-SAN.png" alt="IP-SAN">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IP-SAN의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          [종류] FCIP(터널링프로토콜 이용, 광역 FC SAN 구축위한 TCP/IP FC 프레임 캡슐
화), iFCP(gateway방식, FC스토리지 장비 직접 IP NW에 확장), iSCSI(SCSI 명령을
IP패킷 캡슐화하고, IO블록 data는 TCP/IP NW통해 전달, 가장높은 가용성, 관리
수월, IPSec지원, 저렴)

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
