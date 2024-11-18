---
title: 상호배제
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
      I. 프로세스 병행제어, 상호배제
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 상호배제의 정의
        </div>
        <div class="para-cntnt">
            멀티프로세스 환경에서 특정 프로세스 임계구역 접근시 다른 프로세스의 동시성 제어기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 상호배제
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 상호배제의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/상호배제.png" alt="상호배제">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 상호배제의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구현방법 테스인 데피램
  하드웨어
    Test &amp; Set - 단일 word 검사, 변경수행
    Swap - 다중 word 내용 원자적 교환
    인터럽트 금지 - 임계영역 실행완료까지 차단
  소프트웨어
    데커 알고리즘 - 공유변수와 순서 설정 / 나먼저 쓰고 양보할께 
    피터슨 알고리즘 - 의사표시 및 순서양보 가능 / 너먼저써 난 다음에쓸게
    램포트 알고리즘 - 분산처리 환경 상호배제 / 번호표 순서대로 쓰자 
상호배제 활용기법 뮤세스모
  OS 레벨   
    뮤택스 - locking과 unlocking 사용 상호배제 기법
    세마포어 - P연산과 V연산 상호배제 기법
    스핀락 - Busywaiting 이용한 상호배제 기법
  프로그램언어 레벨
    모니터 - 세마포어 타이밍문제 해결 위한 기법

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
