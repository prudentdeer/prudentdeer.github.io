---
title: 퍼듀 모델
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
      I. ICS 네트워크 구조를 시각화한 퍼듀 모델
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 퍼듀 모델의 정의
        </div>
        <div class="para-cntnt">
            기업구조 참조모델 PERA에서 파생된 산업제어시스템의 6단계 보안 참조모델
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 퍼듀 모델
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 퍼듀 모델의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/퍼듀-모델.png" alt="퍼듀 모델">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 퍼듀 모델의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 네비사영기프
  Level 5 - 기업 네트워크 - 비즈니스결정, 데이터 제공
  Level 4 - 비즈니스, 물류 - db, 앱서버, 파일서버 등
  Level 3 - 사이트운영 - 도메인서버, 프록시서버, db 복제서버
  Level 2 - 영역통제 - HMI 이용 모니터링, 관리
  Level 1 - 기본통제 - 배치, 분산, 프로세스 제어
  Level 0 - 프로세스 - 센서, 액추에이터, 벨브, 펌프

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
