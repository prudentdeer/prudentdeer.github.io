---
title: 전송계층
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
      I. 전송 계층, 4계층
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 전송계층의 정의
        </div>
        <div class="para-cntnt">
            신뢰성 있는 데이터를 송수신하기위해 오류제어, 흐름제어, 혼잡 제어 역할수행하는 4계층
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 전송계층
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 전송계층의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/전송계층.png" alt="전송계층">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 전송계층의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          프로토콜 
  TCP - 전송제어프로토콜, 네트워크의 정보전달을 통제하는 프로토콜 (Transmission Control Protocol)
  UDP - 비연결성이고 신뢰성이 없으며, 순서화되지 않은 Datagram 서비스 제공 (User Datagram Protocol)
역할 오흐혼
  오류제어 - 오류 발생 시 CRC이용, 송신측에 프레임 재전송 요청
  흐름제어 - 수신측에서 설정한 윈도우 크기 만큼 응답(ACK)없이 전송하여 흐름 조절
  혼잡제어 - 느린 출발, 혼잡 회피, 손실 복구, Fast recovery
오류종류 백지에잡지감
  감쇠 현상 (Attenuation) - 거리가 멀어질수록 전송 신호의 세기가 약해지는 현상 / 증폭기(Amplifier), 리피터(Repeater)
  지연 왜곡 (Delay Distortion) - 전송 매체를 통해 전송되는 신호의 속도가 주파수에 따라 차이가 발생하여 간섭이 발생
  잡음 (Noise) - 데이터 전송 시 전송 신호에 다른 불필요한 신호가 더해져서 데이터에 손상을 주는 현상 / 열, 상호 변조, 누화, 충격
  에코 (Echo) - 전송한 신호가 다시 돌아오는 현상
  지터 (Jitter) - 데이터 전송 시 전송 신호의 위상이 일시적으로 일그러지는 현상
  백색 잡음 (White Noise) - 전 주파수에서 발생하는 잡음

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
