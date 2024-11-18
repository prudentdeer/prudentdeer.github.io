---
title: 하이퍼바이저
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
      I. 전통적인 서버 가상화 기술, 하이퍼바이저
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 하이퍼바이저의 정의
        </div>
        <div class="para-cntnt">
            호스트 컴퓨터에서 다수의 운영체제를 동시에 실행하기 위한 논리적 소프트웨어 가상화 플랫폼 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 하이퍼바이저
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 하이퍼바이저의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/하이퍼바이저.png" alt="하이퍼바이저">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 하이퍼바이저의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형
  호스트타입
    Bare-Metal - 하드웨어 컨트롤 관리기능에 따라 두가지로 분류
      전가상화 - Guest OS의 수정이 필요 없도록 H/W 전체를 가상화 하는 기술
      반가상화 - Guest OS를 수정하여 특정 명령이 수행될 때 Hypercall을 호출하여 하이퍼바이저가 실행되도록 하는 기술
    Hosted - 호스트 OS 위에서 응용프로그램으로 구동 / VirtualBox, Parallels Desktop / 상대적 저성능
  하드웨어
    VT-x - 인텔 제공
    AMD-V - AMD 제공
전가상화, 반가상화 비교
  가상화 - HW 전체 &lt;&gt; HW 일부
  성능 - 높은 오버헤드 &lt;&gt; 낮은 오버헤드
  호환성 - 수정 없이 OS 지원 &lt;&gt; 수정된 OS 필요
  유연성 - 높은 유연성 &lt;&gt; 낮은 유연성

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
