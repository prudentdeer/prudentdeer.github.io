---
title: 특권레벨
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
      I. Protection Ring, 운영체제 특권레벨
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 특권레벨의 정의
        </div>
        <div class="para-cntnt">
            운영체제가 하드웨어, 자원접근 제한위해 Ring 0~3으로 특권레벨 구분하여 운영하는 권한레벨
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 특권레벨
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 특권레벨의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/특권레벨.png" alt="특권레벨">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 특권레벨의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특권레벨 커디디앱
  Ring 0 / 커널 - 운영체제 실행모드, 스케쥴링, 인터럽트, IO
  Ring 1 / 디바이스 - 디바이스, 드라이브, 운영체제
  RIng 2 / 디바이스 - 디바이스, 드라이브 
  Ring 3 / 앱 - 응용프로그램 실행, 시스템 콜
이중모드 커유
  커널모드 / Mode 0 - OS가 사용
  유저모드 / Mode 1 - 응용 프로그램이 사용

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
