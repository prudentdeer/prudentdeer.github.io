---
title: 부트로더
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
      I. [정의] 운영체제가 시동되기 전에 미리 실행되면서 커널이 올바르게 시동되기 위해 필요한 모든 관련 작업을 마무리하고 운영체제를 시동시키기 위한 프로그램
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 부트로더의 정의
        </div>
        <div class="para-cntnt">
          [절차] HW초기화(프로세스,메모리,NW,직렬포트), 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 부트로더
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 부트로더의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/부트로더.png" alt="부트로더">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 부트로더의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          자동부트(커널/이미지 실행), 
입력명령처리(간단디버깅,IP주소,자동부팅,보드환경설정), 
커널로딩 및 스타트(커널/루트파일 메모리로딩,커널시작번지로 점프 커널 부팅)
[종류] LILO(리눅스,in MBR),GRUB(GNU,쉘인터페이스),U-BOOT(PowerPC와 ARM,
임베디드), BLOB(ARM,GPL,Serial)

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
