---
title: 클락, 윌슨 모델
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
      I. 클락 윌슨 모델
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 클락, 윌슨 모델의 정의
        </div>
        <div class="para-cntnt">
            3가지 무결성 목표제시, 직무분리와 감사기능이 포함된 무결성을 강조 상업적 모델
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 클락, 윌슨 모델
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 클락, 윌슨 모델의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/클락,-윌슨-모델.png" alt="클락, 윌슨 모델">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 클락, 윌슨 모델의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          3가지 무결성 목표
  비인가자 수정방지
  내외부 일관성 유지
  직무분리 - 합법적 사람에 의한 불법수정 방지
구성요소
  데이터
    CDI - 무결성 보존데이터 항목, Constrained Data Item
    UDI - TP를 통하지 않고 수정 가능한 데이터 항목, Unconstrained Data Item
  프로시저
    TP - 정형화된 트랜잭션을 통해 CDI를 조작하여 무결성 상태 변환, Transformation Procedure
    IVP - 주기적으로 모든 CDI와 외부현실과의 무결성 확인, Integrity Verification Procedure

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
