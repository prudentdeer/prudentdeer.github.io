---
title: 개방형 연결데이터LOD
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
      I. 공공데이터의 개방형 플랫폼, LOD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 개방형 연결데이터LOD의 정의
        </div>
        <div class="para-cntnt">
            웹 상에 존재하는 데이터를 URI 이용 식별처리하여 링크정보를 부여한 개방형 오픈 데이터
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 개방형 연결데이터LOD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 개방형 연결데이터LOD의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/개방형-연결데이터LOD.png" alt="개방형 연결데이터LOD">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 개방형 연결데이터LOD의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          원칙 (팀버너스리가 권고한 4원칙) 
  URI 사용 - 개별 객체에 각각 URI 부여 
  HTTP 프로토콜 사용 - 데이터에 대한 정보의 요청과 응답을 HTTP를 활용 
  RDF, SPARQL 사용 - RDF, SPARQL과 같은 표준을 활용해서 유용한 정보 제공 
  링크 정보의 부여 - 시멘틱 웹을 위해 풍부한 링크 정보를 부여
구축절차 생관발협
  생성단계 - Linked Data를 위한 모델 및 지식 베이스 생성
  관리단계 - 대용량 Linked Data 저장, 관리, 질의처리,추론지원
  발행단계 - 서비스에 따라 SPARQL Endpoint 접점을 생성하고 Linked Data 발행
  협업단계 - Linked Data를 통한 협업 설계
구성요소 UXR SOR 응신질속마개
  구조
    URI - 인터넷에 존재하는 각종 객체
    XML - 언어를 표현하는 메타언어
    RDF - 정보 자원이나 구조표현
  언어
    Ontology - semantic web을 완성
    SPARQL - 온톨로지 질의 언어
    RDFS - RDF 형식 언어
팀 버너스리의 오픈데이터의 등급 오구범유다
  ★              / PDF - 오픈 라이센스, OL(On-Line)
  ★★          / Excel - 구조화 데이터, OL + RE(REadable)
  ★★★       / CSV - 범용형식, OL + RE + OF(Open Format)
  ★★★★    / RDF - URI 개체식별, OL + RE + OF + URI
  ★★★★★ / LOD - 다른데이터 링크가능, OL + RE + OF + URI + LD (Linked Data) 
- 최근 국립중앙도서관이 LOD 서비스 제공시작

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
