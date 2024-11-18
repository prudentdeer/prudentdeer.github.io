---
title: ARQ
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
      I. ARQ 의 개요
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ARQ의 정의
        </div>
        <div class="para-cntnt">
            데이터 교환 중 오류가 검출되면 부정응답 수신후 오류프레임을 재전송하는 오류정정 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. ARQ
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ARQ의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/ARQ.png" alt="ARQ">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. ARQ의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          발생경우 상실확
  손상된 프레임 - 수신측에서 수신하였으나 데이터를 인식하지 못함
  손실된 프레임 - 수신측에 프레임이 도착하지 않은 경우
  손실된 확인응답 - 수신측 응답이 송신측에 도착하지 않은 경우
오류정정 스고샤
  Stop and Wait ARQ - 1개의 프레임을 송신하고, 에러 유무를 판단
  Go-Back-N ARQ - 손상 프레임 이후 모든 프레임을 재전송
  Selective-Repeat ARQ - 손상된 프레임만 재전송하는 방식
  Hybrid ARQ - FEC 방식을 적용해 오류를 수정하고 수정 안된 프레임만 재전송하는 방식
  Adaptive ARQ - 블록의 길이를 동적으로 변경할 수 있는 방식

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
