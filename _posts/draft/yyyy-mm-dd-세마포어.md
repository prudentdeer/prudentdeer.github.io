---
title: 세마포어
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
      I. 상호배제를 이용한 동기화 기법, 세마포어 - OS 레벨
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 세마포어의 정의
        </div>
        <div class="para-cntnt">
            임계영역의 동시성제어 위해 P연산과 V연산을 이용한 N개 스레드 대상 상호배제 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 세마포어
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 세마포어의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/세마포어.png" alt="세마포어">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 세마포어의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 PV 이계 SS
  P 연산 / S - 1 - 잠금을 수행하는 코드로 S 가 0 보다 크면 1 만큼 감소 시키고 임계영역 진입 - S 가 0 보다 작으면 0 보다 커질때까지 대기
  V 연산 / S + 1 - 잠금 해제와 동기화를 같이 수행하는 코드로 S 값을 1 증가 - 세마포어에서 대기 중인 프로세스에게 임계영역에 진입하도록 신호 전달
  이진&nbsp;세마포어 (Binary) -&nbsp;정적변수는&nbsp;0&nbsp;또는&nbsp;1&nbsp;의&nbsp;값만&nbsp;할당&nbsp;가능한&nbsp;세마포어
  계수형&nbsp;세마포어 (Counter) -&nbsp;사용&nbsp;가능한&nbsp;자원의&nbsp;수로&nbsp;초기값&nbsp;설정
  Segment() - get 함수의 처리
  Semctrl() - 통제함수 처리
세마포어, 모니터, 뮤택스의 비교
  기반 - OS &lt;&gt; 프로그래밍언어 &lt;&gt; OS
  기법 - P, V연산 &lt;&gt; 베타, 조건 큐 &lt;&gt; Lock, Unlock
  해결 - 상호배제 &lt;&gt; 타이밍 문제 &lt;&gt; 상호배제
  사용 - N개 스레드 &lt;&gt; 1개 스레드 &lt;&gt; 1개 스레드

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
