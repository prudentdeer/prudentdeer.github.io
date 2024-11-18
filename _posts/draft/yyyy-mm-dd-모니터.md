---
title: 모니터
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
      I. 세마포어의 타이밍 문제 해결, 모니터의 개념 - PROGRAMMING 레벨
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 모니터의 정의
        </div>
        <div class="para-cntnt">
            세마포어 타이밍문제 해결 위해 프로그래밍 언어수준에서&nbsp;상호배제를&nbsp;구현한 상호배제 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 모니터
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 모니터의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/모니터.png" alt="모니터">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 모니터의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 임베조 싱웨노
  동기화 요소
    임계구역 -&nbsp;쓰레드에서&nbsp;접근하는&nbsp;공유&nbsp;자원&nbsp;영역
    베타동기&nbsp;큐 -&nbsp;한&nbsp;쓰레드만&nbsp;임계영역에&nbsp;접근하도록&nbsp;제어하는&nbsp;큐
    조건동기&nbsp;큐 -&nbsp;쓰레드를&nbsp;조건에&nbsp;따라&nbsp;잠그거나&nbsp;깨우는&nbsp;큐
  언어 요소 (Java&nbsp;사례)
    Synchronized -&nbsp;베타동기큐로 진입시키는 키워드
    Wait -&nbsp;임계구역에서&nbsp;조건동기&nbsp;큐로&nbsp;진입시켜&nbsp;쓰레드를&nbsp;잠금
    Notify,&nbsp;notifyAll -&nbsp;조건동기&nbsp;큐에&nbsp;잠겨&nbsp;있는&nbsp;쓰레드를&nbsp;깨워&nbsp;임계구역에&nbsp;재진입
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
