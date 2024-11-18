---
title: UDP
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
      I. 일방적 데이터 전송, UDP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. UDP의 정의
        </div>
        <div class="para-cntnt">
            RFC 768 표준 오류제어, 흐름제어, 혼잡제어 없이 비연결지향 실시간 전송계층 프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. UDP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. UDP의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/UDP.png" alt="UDP">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. UDP의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  실시간 전송 - 실시간 빠른 전송이 가능하여, 실시간 음성/방송 서비스에 적합
  비연결형 - 목적지와 연결 설정이 없는 비 연결형 서비스
연결관리
  연결 / Request, Response
  해제 / 절차없음
구성요소 발수길체포
  발신포트번호 - 발신지 호스트상에서 수행되는 프로세스가 사용하는 포트 번호
  수신포트번호 - 목적지 호스트상에서 수행되는 프로세스가 사용하는 포트 번호
  길이 - 헤더와 데이터를 합한 사용자 데이터그램의 전체 길이를 정의
  체크섬 - 사용자 데이터그램에 오류가 있는지 여부를 검사
  포트번호 - 프로세스 대 프로세스를 정의하기 위한 식별자

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
