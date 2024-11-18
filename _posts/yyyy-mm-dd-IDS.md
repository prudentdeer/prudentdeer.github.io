---
title: IDS
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 보안]
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
      I. 실시간 침입탐지시스템, IDS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IDS의 정의
        </div>
        <div class="para-cntnt">
            비인가 사용자, 외부 침입자의 불법적 침입, 보안정책 위반행위 실시간으로 탐지하는 시스템
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IDS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IDS의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IDS.png" alt="IDS">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IDS의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  모방성, 동시성, 추적성, 즉시 대응성
주요기능 경세실리
  경보기능, 세션차단기능, 실시간 탐지, 리포팅
구성요소 정정로이패패
  정보 수집기 - 호스트나 네트워크로부터 분석 자료 수집
  정보 분석기 - 시스템 설정과 패턴 DB 설정에 따라 정보 분석
  로그 저장소 - 분석된 결과 저장
  이벤트 보고기 - 로그 저장소의 분석 결과를 해당 관리자에게 보고
  패턴 생성기 - 침입 분석 자료를 통해 패턴을 생성
  패턴 DB - 패턴 생성기에 의해 생성된 패턴의 저장관리

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
