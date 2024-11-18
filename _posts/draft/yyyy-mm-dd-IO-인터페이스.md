---
title: IO 인터페이스
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
      I. 입출력 포트(I/O Port), 입출력장치 인터페이스
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IO 인터페이스의 정의
        </div>
        <div class="para-cntnt">
            컴퓨터 내부장치와 외부장치간 이진정보 전송 위한 방법제공 입출력 인터페이스
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IO 인터페이스
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IO 인터페이스의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IO-인터페이스.png" alt="IO 인터페이스">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IO 인터페이스의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          매커니즘
  USB / 데이터 - 키보드, 마우스, 프린터, 외장 하드 드라이브, 카메라
  HDMI / 멀티미디어 - 모니터, 텔레비전, 비디오 장치 등
  Ethernet / 네트워크 - 라우터, 스위치, 네트워크 카드
필요성 전처장에
  전송속도 - 입출력장치와 CPU 동작속도 차이 / 데이터 버퍼(I/O data buffer) 이용
  처리단위 - 주기억장치 word, 입출력장치 byte / 범용 데이터 버퍼를 사용
  입출력장치 번호지정 - 여러 개 입출력 장치 / 장치의 번호를 지정
  에러율 - 입출력시 발생하는 에러 / 오류검출 비트 첨부, 식별
전송방식 종류 프인디채
  중앙처리장치 관여
    Program I/O - 원하는 I/O 가 완료되었는지의 여부를 CPU 가 상태 Flag 를 계속 조사
    Interrupt I/O - 데이터 전송준비가 되면 입·출력 IF가 시스템에 알려 입·출력 수행
  중앙처리장치 독립
    DMA - 입·출력장치가 직접 주기억장치를 접근하여 Data Block 을 입·출력
    Channel - I/O 를 위한 특별한 명령어를 I/O 프로세서에게 수행토록 하여 입·출력 제어

- 대표적 인터페이스인 USB는 3.2 표준까지 발표

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
