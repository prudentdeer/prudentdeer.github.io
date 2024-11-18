---
title: HIL
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
      I. Hardware-in-the-loop 시뮬레이션
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. HIL의 정의
        </div>
        <div class="para-cntnt">
            가상환경에서 집중적으로 테스트할 컴포넌트들을 closed loop 에서 실시간 시뮬레이션 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. HIL
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. HIL의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/HIL.png" alt="HIL">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. HIL의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  하드웨어
    Host PC - 사용자 인터페이스, 모델과 구현 소프트웨어 실행
    전기로드 - 실제 로드 또는 전기적으로 동일한 회로
    컴포넌트 - 실제 컴포넌트가 필요
    전원장치 - 가변적으로 전압을 설정할 수 있는 전원 장치
  소프트웨어
    운영 소프트웨어 - 구현 및 실험 소프트웨어
    실시간 소프트웨어 - I/O 처리율을 최대화하고 I/O 지연(latency)을 최소화
    Dynamic 모델
    HIL 애플리케이션 

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
