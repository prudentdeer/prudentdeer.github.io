---
title: 이더넷
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
      I. 로컬영역의 데이터전송, 이더넷
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 이더넷의 정의
        </div>
        <div class="para-cntnt">
            48비트 MAC 주소를 기반, 네트워크에 연결된 기기간 CSMA/CD 방식 통신하는 네트워크
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 이더넷
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 이더넷의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/이더넷.png" alt="이더넷">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 이더넷의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  CSMA/CD - 버스형인 이더넷은 액세스방식으로 CSMA/CD방식을 채용
  프레임 - 맥 계층에서 정의된 프레임 구조에 맞게 포장
  허브 - 한 대의 허브가 중심이 되어 여러 대의 컴퓨터와 네트워크 장비를 연결
  스위치 - 전이중 통신 방식이 가능하여 네트워크 속도가 향상
케이블 동트광
  동축 케이블 / TV, 안테나 - 하나의 굵은 구리선을 여러겹으로 감싼 형태
  트위스티드페어 케이블 / 유연성 - 두 개 이상의 구리 도선이 꼬아진 형태
  광 케이블 / 빛 전송 - 광섬유를 몇 백 가닥씩 묶어 케이블로 만든 형태
프레임 구성요소 플스 대성타 다FCS
  물리헤더
    Preamble / 7byte : 시스템에 들어오는 프레임을 수신하게 하고 입력 타이밍을 맞춤 (서문)
    SFD / 1byte : 두 번째 필드 프레임의 시작을 알리는 역할 (Start Frame Delimiter, 시작프레임식별자)
  MAC 헤더
    DA / 6byte : 패킷을 수신하는 목적지 지국 또는 지국들의 물리주소 (Destination Address)
    SA / 6byte : 패킷 송신자의 물리주소 포함 (Source Address)
    Type / 2byte :  상위계층 프로토콜을 나타내는 유형필드
  LLC 프레임
    Data / 46~1500byte : 상위 계층 프로토콜로부터 캡슐화된 데이터를 전달
    FCS / 4byte : 각 전송 패킷의 전송 에러 체크에 사용 (Frame Check Sequence)

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
