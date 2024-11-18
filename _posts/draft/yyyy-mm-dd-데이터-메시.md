---
title: 데이터 메시
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
      I. 탈중앙화 관리, 데이터 메시
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 메시의 정의
        </div>
        <div class="para-cntnt">
            데이터 Silo 현상 해결위해 데이터를 도메인기반 독립된 DP로 관리하는 탈중앙화 아키텍처
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 데이터 메시
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 메시의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/데이터-메시.png" alt="데이터 메시">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 데이터 메시의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          기술요소 페도대셀 OAD
  4원칙
    Federated Governance - 상호 운용을 위한 표준을 따르는 생태계로 운영
    Domain Ownership - 소유권을 도메인을 기준으로 나누어 확장성 대응
    Data As A Product - 쉽게 검색이 가능하고 품질이 보장된 데이터를 사용하며 생산성이 증가
    Self-Serve Data Platform - 각 도메인 팀이 자율적으로 제품을 만들고 사용할 수 있도록 지원
  아키텍처
    Operation Plane - 운영 데이터
    Analytical Plane - 분석 데이터
    Delivery Plane - 데이터 활용분야
데이터 메시와 데이터 패브릭 비교
  구조 - 탈중앙화 &lt;&gt; 중앙 집중식
  소유권 - 분산 소유권 &lt;&gt; 중앙화 소유권
  특징 - Data as a product &lt;&gt; Data is a by-product
https://carlosgrande.me/my-data-mesh-thesis/

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
