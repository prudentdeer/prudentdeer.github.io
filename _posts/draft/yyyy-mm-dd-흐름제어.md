---
title: 흐름제어
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
      I. 수신 데이터처리 위한 송신측 데이터제한, 흐름제어
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 흐름제어의 정의
        </div>
        <div class="para-cntnt">
            수신측의 처리속도와 저장문제 해결위해 전송 측에서 데이터의 양을 제한하는 흐름제어기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 흐름제어
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 흐름제어의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/흐름제어.png" alt="흐름제어">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 흐름제어의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          방법 송전슬스
  송신제어 - 한번에 1개씩 수신 확인하며 프레임을 전송
  전송률 기반 - 데이터 송신률에 대한 임계 값 관리
  슬라이딩 윈도우 - 여러 개의 프레임을 동시에 보내고자 하는 흐름제어
  Stop and Wait - 단순한 형태의 자동 재전송 요구(ARQ)

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
