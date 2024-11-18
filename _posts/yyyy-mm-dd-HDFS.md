---
title: HDFS
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 데이터베이스]
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
      I. Hadoop의 핵심 분산 파일 저장기술 HDFS의 개념
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. HDFS의 정의
        </div>
        <div class="para-cntnt">
            대용량 데이터 집합을 처리위해 Namenode 와 다수 Datanode 이용한 분산 파일 시스템
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. HDFS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. HDFS의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/HDFS.png" alt="HDFS">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. HDFS의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징 
  Fault-Tolerant, Data Block, Replication, Rack Awareness
구성요소
  Name Node - 파일시스템의 Metadata(디렉터리구조, Access 권한 등) 관리 서버
  Backup Node - Name Node 의 Metadata 로드가 실패 시 Backup Node 로 사용
  Data Node : 실제 데이터를 저장 유지하는 서버, Data Node 간에는 데이터 복제를 통해 데이터의신뢰성 유지함
운영구조
  Replication - Data Node 간 정보를 복제, 분산저장으로 HA 구현
  TCP/IP - 모든 HDFS 통신 프로토콜은 TCP/IP 구조, RPC
  Name Space - HDFS 는 전통적인 계층적 파일 구조 지원, 호환성 확보

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
