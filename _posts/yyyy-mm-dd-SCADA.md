---
title: SCADA
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 디지털서비스]
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
      I. 원거리 감시와 제어, SCADA 시스템
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SCADA의 정의
        </div>
        <div class="para-cntnt">
            RTU, PLC 를 통해 원격 공정데이터 수집하고 작업공정을 감시, 제어하는 산업제어 시스템
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SCADA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SCADA의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SCADA.png" alt="SCADA">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SCADA의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  경보, 감시/제어, 지시/표시, 누산기
구성요소 운통데감 HRPS
  시스템
    운전철학 - 기온/진동/전압변동에 높은 내구력을 갖도록 설계
    통신시설 - 데이터 수집 및 제어 명령어 전달에 사용되는 유무선 통신 기술
    데이터베이스 - RTU, PLC에서 수집된 데이터를 누적하여 저장하는 역할
    감시시스템 - 프로세스와 관련된 자료를 수집하고, 하드웨어 제어를 위한 실질적인 명령어
  기술요소
    HMI - 기계 제어에 사용되는 데이터를 인간에게 친숙한 형태로 변환하여 보여줌
    RTU - 센서와 직접 연결되어 디지털신호 변환 Remote terminal unit
    PLC - 프로그래밍가능한 실제 설치 기기
    Security - 폐쇄적인 기술에서 공개된 기술로 이전으로 보안문제 대두

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
