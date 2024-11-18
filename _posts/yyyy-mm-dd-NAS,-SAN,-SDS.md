---
title: NAS, SAN, SDS
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
      I. Storage 구축방법의 정의
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NAS, SAN, SDS의 정의
        </div>
        <div class="para-cntnt">
          - NAS (Network Attached Storage): 일종의 파일서버로 운영체제가 별도로 존재하며 이더넷 등 네트워크로 연결 .(파일시스템 공유 가능, 중규모)
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. NAS, SAN, SDS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NAS, SAN, SDS의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/NAS,-SAN,-SDS.png" alt="NAS, SAN, SDS">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. NAS, SAN, SDS의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          - SAN (Storage Area Network): 하드 수십~수백 개가 존재하는 SAN 스토리지에 fiber 채널 스위치를 이용하여 고속 연결이 가능한 데이터 전용망(대규모)
- IP-SAN: SAN 네트워크를 IP 네트워크를 통해 확장시켜 거리의 제한을 극복 - FAN): NAS/SAN 등 네트워크 스토리지의 파일시스템을 기반으로 사용자 파일 데이터 전송 및 가상화 등의 서비스를 제공하는 네트워크 
- SDS (Software Defined Storage): 스토리지 서비스 또는 스토리지 소프트웨어를 추상화하여 하드웨어에서 스토리지 소프트웨어를 분리하는 스토리지 아키텍처

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
