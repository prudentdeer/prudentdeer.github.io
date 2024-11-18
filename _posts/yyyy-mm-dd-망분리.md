---
title: 망분리
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
      I. 내외부의 연결차단, 망분리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 망분리의 정의
        </div>
        <div class="para-cntnt">
            외부 인터넷망을 통한 불법접근과 정보유출 차단위해 업무망과 외부망을 분리하는 차단조치
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 망분리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 망분리의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/망분리.png" alt="망분리">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 망분리의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 이전서클
  물리적망분리
    2PC - 2대의 PC를 이용한 네트워크 분리
    전환장치 - 하드디스크, IP 주소, 라우팅 정보 등 네트워크 연결 자원을분리
  논리적망분리
    서버 가상화 - 가상화 서버를 통한 내부망 또는 외부망 접근
    클라이언트 가상화 - 사용자 PC에 가상머신생성 OS영역 분리

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
