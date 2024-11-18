---
title: 인터럽트
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 운영체제]
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
      I. 인터럽트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 인터럽트의 정의
        </div>
        <div class="para-cntnt">
            CPU가 처리하던 작업을 중단하고 특수사건이나 환경을 처리할 수 있도록 보내는 제어신호
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 인터럽트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 인터럽트의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/인터럽트.png" alt="인터럽트">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 인터럽트의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 요처서트
  인터럽트 요청 (IRQ) - CPU에 인터럽트를 요청하는 신호
  인터럽트 처리루틴 (IPR) - 인터럽트 발생 원인을 찾아 ISR 호출
  인터럽트 서비스루틴 (ISR) - 인터럽트에 대한 실체 처리를 담당
  트랩 (Trap) - 오류나 사용자에 의해 발생시킨 인터럽트
종류 전기외입 프슈
  외부 인터럽트
    전원이상 인터럽트 - 예기치 못한 정전이나 Power 모듈 이상에 따른 인터럽트
    기계착오 인터럽트 - CPU의 기능적인 오류에 의한 인터럽트
    외부신호 인터럽트 - 자원의 할당된 시간이 종료된 경우
    입출력 인터럽트 - 입출력 장치가 데이터 전송을 요구하거나 전송이 끝나 다음동작이 수행되어야 할 경우
  내부 인터럽트
    프로그램검사 인터럽트 - 오버플로우(Overflow), 언더플로우(Underflow) 발생, 예외 처리(Exception)
  소프트웨어 인터럽트
    SVC(Super Visor Call) 인터럽트 - 프로그램 처리 중 명령의 요청에 의해서 발생
우선순위
  직렬, 병렬, 폴링

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
