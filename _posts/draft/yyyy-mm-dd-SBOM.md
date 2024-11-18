---
title: SBOM
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
      I. SW 공급망 투명성 확보방안, SBOM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SBOM의 정의
        </div>
        <div class="para-cntnt">
            SW 공급망 투명성 확보 위해 소프트웨어 컴포넌트 관련 메타정보를 기록한 자재명세서
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SBOM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SBOM의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SBOM.png" alt="SBOM">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SBOM의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          등장배경
  안전한 공급망 관리 필요 - 디지털 전환 가속 / 소프트웨어 중심사회 고도화 / 소프트웨어의 역할의 중요성이 커짐
  오픈소스 활용 증가 - 오픈소스 SW(OSS) 활성화, 모듈화, 재사용 증가 영향
구성요소 공고의작 버해이
 기본 정보
    공급자 이름 - 구성요소를 만들고 정의하고 식별하는 주체의 이름
    고유 식별자 - HASH 외에 식별을 위한 고유의 역할을 하는 기타 식별자
    의존관계 - 소프트웨어 구성 요소 의존 관계
    SBOM 작성자 - 저작권 정보(SBOM 데이터를 만든 주체의 이름)
  컴포넌트 정보
    컴포넌트 이름 - 최초 공급자에 의해 정의된 소프트웨어 단위의 명칭
    컴포넌트 버전 - 공급자가 이전에 식별된 소프트웨어 버전으로부터의 변경을 명시하기 위해 사용하는 식별자
    컴포넌트 HASH - 소프트웨어 식별을 위한 고유의 일방향 암호화 값
SBOM 표준 포맷 
  SPDX / 포괄성과 유연성 - SBOM을 교환하기 위한 개방형 표준, Software Package Data Exchange
  SPDX 라이트 / 경량성 - 전체 SPDX가 필요하지 않은 경량하위 집합
  사이클론DX / 보안, 규정준수 - 사이버 보안을 위한 분석에 사용하도록 설계
  SWID / 이력관리 - 제품 이름 및 버전에 대한 세부 정보가 포함된 레이블, Software Identification
- 미국과 유럽의 SBOM 의무화, 국내도 필요

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
