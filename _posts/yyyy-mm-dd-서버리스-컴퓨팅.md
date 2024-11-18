---
title: 서버리스 컴퓨팅
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
      I. 클라우드 패러다임 전환, 서버리스 컴퓨팅
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 서버리스 컴퓨팅의 정의
        </div>
        <div class="para-cntnt">
            관리영역 없이 앱 개발하기위해 On demand, Event 기반으로 CSP가 서버를 관리하는 컴퓨팅 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 서버리스 컴퓨팅
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 서버리스 컴퓨팅의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/서버리스-컴퓨팅.png" alt="서버리스 컴퓨팅">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 서버리스 컴퓨팅의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          기술요소
  프론트엔드
    API 게이트웨이 - Event Trigger, Load Balancing
    RESTFul API - URL 기반, Custom Code 호출
  백엔드
    이벤트 라우터 - 이벤트 전달, 기능 서비스
    BaaS - 인증, 구매 등 보안 필요 기능
  Function 서비스
    FaaS - 독립실행 서비스, 기능 단위
    컨테이너 - Docker 기반 신속 배포/릴리즈
    OAuth - 사용자 인증
서버리스, PaaS 비교
  인프라관리 - CSP &lt;&gt; 일부 관리
  비용 - Pay per use &lt;&gt; 서버 및 용량에 따라 비용 결정
  할당 - Ondemand &lt;&gt; 오토스케일링

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
