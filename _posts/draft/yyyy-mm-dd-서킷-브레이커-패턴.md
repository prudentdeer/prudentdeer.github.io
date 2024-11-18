---
title: 서킷 브레이커 패턴
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 소프트웨어공학]
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
      I. MSA 장애전파 방지, 서킷브레이커 패턴
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 서킷 브레이커 패턴의 정의
        </div>
        <div class="para-cntnt">
            실패하는 요청을 계속 하지않기 위해 문제가 발생한 지점을 감지하고 격리하는 디자인패턴
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 서킷 브레이커 패턴
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 서킷 브레이커 패턴의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/서킷-브레이커-패턴.png" alt="서킷 브레이커 패턴">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 서킷 브레이커 패턴의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          3가지 상태 클오하
  Closed - 모든 것이 정상인 상태
  Open - 외부에 장애가 발생한 상황
  Half Open - Open 상태가 되고 일정 시간이 지난 상황, 일부 허용된 요청들이 성공할 경우 Closed상태로 전환

Circuit breaker 패턴은 server A와 server B사이에 circuit breaker를 구성
server A가 server B을 호출할 때 circuit breaker가 모든 트래픽을 bypass 함
이때 server B에 응답이 없다면 circuit breaker가 server B로의 호출을 강제로 끊고 server A에게 에러 메시지를 날림

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
