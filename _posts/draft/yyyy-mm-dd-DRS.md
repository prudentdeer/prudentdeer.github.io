---
title: DRS
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 경영전략]
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
      I. 비즈니스 연속성을 위한 시스템, DRS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DRS의 정의
        </div>
        <div class="para-cntnt">
            기업의 업무연속성 보장하기 위해 조직, 정보자원, 복구절차를 대비하는 Failover 시스템
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DRS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DRS의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DRS.png" alt="DRS">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DRS의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          필요성
  재난시 연속성필요 / 신뢰도하락 방지 / 기업 비용손실 방지
기술요소 고결디샌패패
  특성
    고가용성 - 최단 복구를 위한 H/W Clustering 또는 Stand-By 형태
    결함허용성 - 실시간 복구가 가능한 Dual 시스템
  요소기술
    SAN - 대량의 데이터를 보관하고 공유하여 사용하는 기술
    DWDM 고밀도파장분할다중화 (Dense Wavelength Division Multiplexing) - 고속의 Data 전송을 위한 통신
운영방식 미핫웜콜
  Mirror Site - 동시에 데이터를 처리 및 운영 / RTO = 0
  Hot Site - 거의 동일한 수준의 자원 확보, 데이터 실시간 이중화 / RTO &lt;= 2H
  Warm Site - 일부 장비를 구비하고, 재해발생 시 주요 업무만 복구 / RTO &lt; 1W
  Cold Site - 기본시설만 확보하고 재해 발생 시 구축 / RTO &gt;= 수개월
시스템 운영형태별 구축유형 상공외독
  상호 계약형 - 평소 상호 원조 관계를 갖고 비상시 지원하는 형태 / 신규투자 절감 / 상호시스템 변경 작업 종속
  공동 이용형 - 여러 기관이 공동 출자하여 백업센터 건립 운영 / 공동 투자에 따른 비용 절감 / 동시사용시 자원 사용에 제약 발생 가능성
  외부 위탁형 - 재해 복구 전문 서비스 기관에 위탁 운영 / 전문자원기술 활용 가능 / 보안 문제, 기술적 신뢰성
  독자 운영형 - 독자적인 백업센터 구축, 운영 / 데이터 보안 유지, 즉시 대처 용이 / 막대한 구축 비용 소요

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
