---
title: 무중단 배포기법
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
      I. 무중단 배포기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 무중단 배포기법의 정의
        </div>
        <div class="para-cntnt">
            Rolling Update
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 무중단 배포기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 무중단 배포기법의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/무중단-배포기법.png" alt="무중단 배포기법">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 무중단 배포기법의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
              - 일반적인 배포, 인스턴스나 서버단위로 순차배포 
    - 장) 관리 및 롤백 용이
    - 단) 서버 처리 용량 고려
  Blue/Green Deployment 
    - Old 버전을 블루, New 버전을 그린으로 호명
    - New 버전을 모두 배포 후 모든 트래픽을 New 버전으로 한번에 Switching
    - 장) 운영환경에 영향없이 신버전 테스트
    - 단) 자원이 두배로 필요. 비용증가
  Canary Release
    - 트래픽 제어를 통해 일부 사용자만 신규 서버로 접속
    - 모니터링과 디버깅을 수행 한 후 문제가 없는 경우 모든 서버로 교체
    - 장) 장애를 빠르게 감지, A/B 테스트
    - 단) 네트워크 트래픽 제어 부담

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
