---
title: SCSI RDMA(Remote Direct Memory Access)
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
      I. [정의] SCSI 장치 통해 CPU사용 없이 응용어플리케이션 간 원격으로 직접데이터 교환하는 스토리지 원격 접속 프로토콜
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SCSI RDMA(Remote Direct Memory Access)의 정의
        </div>
        <div class="para-cntnt">
          [구성]
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SCSI RDMA(Remote Direct Memory Access)
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SCSI RDMA(Remote Direct Memory Access)의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SCSI-RDMA(Remote-Direct-Memory-Access).png" alt="SCSI RDMA(Remote Direct Memory Access)">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SCSI RDMA(Remote Direct Memory Access)의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          SRP Initiator(SCSI Application, SCSI Disk Driver, SCSI Unifying Layer, SRP Initiator Driver, InfiniBand Driver/HCA)
SRP Target(Front-end Target Driver, SCSI Mid Target Driver, Local SCSI Sub-system)

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
