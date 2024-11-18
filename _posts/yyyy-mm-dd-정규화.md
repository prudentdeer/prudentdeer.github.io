---
title: 정규화
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
      I. 데이터의 일관성과 정확성을 위한 정규화의 개념
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 정규화의 정의
        </div>
        <div class="para-cntnt">
            이상현상을 발생시키는 속성간의 종속성, 중복성을 제거, 무결성 보장위해 릴레이션 분해하는 과정
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 정규화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 정규화의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/정규화.png" alt="정규화">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 정규화의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          기본원칙 정분중구가
  일관성
    정보의 무손실 - 분해된 릴레이션이 표현하는 정보는 분해되기 전의 정보를 모두포함
    분리의 원칙 - 하나의 독립된 관계성은 하나의 독립된 릴레이션으로 분리하여 표현
    중복성 감소 - 최소의 중복으로 여러 이상현상 제거
  사용성
    구조 리팩토링 - 같은 의미의 정보를 유지하면서 더 바람직한 구조로 변환해야 함
    가용성 향상 - 자료검색과 추출의 효율성 추구
정규화 도부이결다조
  1차 정규화 - 도메인이 원자값
  2차 정규화 - 부분함수 종속제거
  3차 정규화 - 이행함수 종속제거
  3.5차 정규화 - 결정자이면서 후보키아닌것 제거
  4차 정규화 - 다치종속 제거
  5차 정규화 - 조인종속 이용

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
