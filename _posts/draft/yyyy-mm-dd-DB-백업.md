---
title: DB 백업
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 데이터베이스]
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
      I. DB 연속성 확보, DB 백업
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DB 백업의 정의
        </div>
        <div class="para-cntnt">
            장애발생시 DB 연속성 확보위해 데이터 복사, 이중화, 실시간복제하여 보관하는 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DB 백업
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DB 백업의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DB-백업.png" alt="DB 백업">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DB 백업의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          필요성
  데이터 재생의 어려움과 비용 : 디스크 오류나 정전에 의해 발생된 데이터 손실은 엄청난 비용과 시간이 소요됨
  값비싼 시스템 중지 : 영위하는 비즈니스 영역에서 수입감소와 직결되고 이로 인한 고객의 불신이탈
  비즈니스 영속성 (BCP) : 데이터 손실로 인한 비즈니스 중단유발과 그로 인한 기업이미지, 신뢰도 상실
백업유형 전증차 온오프 일주월
  데이터 범위
    전체백업 - 백업받고자 하는 데이터의 전체에 대해 백업을 실시하는 방식
    증분백업 - 전체 백업이후 변경분이 누적되어 백업되는 방식
    차등백업 - 전체백업이후로 다음 전체백업이 실시되기 직전까지 이전 전체 백업이후 변화된 데이터를 백업하는 방식
  서비스 제공여부
    온라인 백업 - 백업시 데이터베이스의 다운타임 없이 해당 데이터를 백업하는 방식
    오프라인 백업 - 백업시 데이터베이스를 다운시키고 백업을 받는 방식
  백업주기
    일일백업 - 데이터 베이스 데이터, 로그를 매일 백업작업을 실시함
    주간백업 - 매주 지정된 요일에 실시
    월간백업 - 시스템 예방점검과 연계하여 월1회이상 시스템점검과 월간전체백업 실시

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
