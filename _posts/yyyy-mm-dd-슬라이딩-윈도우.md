---
title: 슬라이딩 윈도우
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
      I. 수신측의 설정크기만큼 전송, 슬라이딩 윈도우
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 슬라이딩 윈도우의 정의
        </div>
        <div class="para-cntnt">
            수신측에서 설정한 크기만큼 확인응답(ACK) 없이 전송할 수 있게 하는 동적 흐름제어 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 슬라이딩 윈도우
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 슬라이딩 윈도우의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/슬라이딩-윈도우.png" alt="슬라이딩 윈도우">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 슬라이딩 윈도우의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  흐름제어 기법 – Transport Layer 제공 흐름제어 기법
  연속 전송 – 응답을 기다리지 않고 연속 패킷 전송
  크기 동적변환 – 윈도우 크기가 상황에 맞게 동적으로 변화
동작설명 열닫축크
  윈도우 열린동작 - 수신측으로부터 ACK가 도착하여 윈도우의 오른쪽 경계가 오른쪽으로 이동하는 현상
  윈도우 닫힘동작 - 데이터가 ACK를 받아 전송되어 윈도우의 왼쪽 경계가 오른쪽으로 이동하는 현상
  윈도우 축소동작 - 수신 측으로부터 NAK를 수신하거나, 타임아웃 발생 시 송신측에서 프레임 재전송
  윈도우 크기 - 수신측 윈도우와 혼잡 윈도우의 크기 중 작은 값으로 결정
[해결방안] Nagle's Algorithn(송신측, 일정크기까지 전송 보류 -&gt; 송신 Data 크기의 적정 수준 유지)
Clark's Solution(수신측, 최소 절반이상 공간 확보 이전에는 rwnd: 0 으로 응답, 송신 방지 -&gt; 요청 Data 크기 적정 수준 유지)

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
