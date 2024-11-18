---
title: 이상현상
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
      I. 정규화가 필요한 이유, 이상현상
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 이상현상의 정의
        </div>
        <div class="para-cntnt">
            데이터의 중복으로 인해 릴레이션에 대한 삽입, 갱신, 삭제 시 발생하는 비합리적 이상현상
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 이상현상
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 이상현상의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/이상현상.png" alt="이상현상">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 이상현상의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          발생원인
  여러 종류의 사실들을 하나의 릴레이션으로 표현하려고 하기 때문에 발생함
  속성들간에 존재하는 여러가지 종속관계에 대해 정규화가 실행되지 않았기 때문에 발생함
종류 삽삭갱
  삽입이상 - 데이터 삽입시 불필요 정보까지도 삽입 / 정규화, 중복제거
  삭제이상 - 데이터 삭제시 원하지 않는 정보까지도 삭제됨 / 제약조건, 참조무결성
  갱신이상 - 특정 값 갱신 시 일부만 갱신되어 불일치현상, 다수갱신필요 / 트랜젝션, 중복제거

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
