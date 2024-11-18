---
title: Star & Snowflake Schema
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
      I. Star Schema 
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Star & Snowflake Schema의 정의
        </div>
        <div class="para-cntnt">
            정규화된 Fact Table을 중심으로 비정규화된 Dimension Table 배치 형태 모델링 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Star & Snowflake Schema
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Star & Snowflake Schema의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Star-&-Snowflake-Schema.png" alt="Star & Snowflake Schema">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Star & Snowflake Schema의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          장점
  성능향상 - 쿼리를 간단하게 구성, 조인 감소
  이해성 - 시스템의 이해성 높으며, 대용량 처리에 적합
단점
  데이터 무결성 감소
  복잡한 쿼리 처리 어려움
  N:M 데이터 관계 적합하지 않음
  데이터 요약 및 정제가 필요함

Snowflake  Schema 
정의
  정규화된 Fact Table을 중심으로 정규화된(제3정규형) Dimension Table 배치 형태 모델링 기법
장점
  적은용량 - 테이블의 저장 공간의 크기 작음
  무결성 유지 - 가 잘 되어 있어 중복이 적어 무결성 유지에 효과적
  호환성 - 여러 OLAP툴과 호환성이 좋아 활용도가 높음
단점
  복잡한 데이터 스키마 구조로 많은 조인 수로 성능의 저하가 발생
  시스템의 복잡성이 증가되어 이해성 저하

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
