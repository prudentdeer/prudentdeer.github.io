---
title: MSA
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 소프트웨어공학]
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
      I. Fine grained, MSA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MSA의 정의
        </div>
        <div class="para-cntnt">
            서비스를 여러 개의 작은 마이크로서비스로 구성하고 REST, API 통신이용 폴리글랏형 아키텍처
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MSA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MSA의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MSA.png" alt="MSA">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MSA의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징 모매미마
  빠른 비즈니스 유연성 위해 사용
구성요소 데게인서클
  API 게이트웨이 / 라우팅, 로드밸런싱 - 상호독립적 API 서비스 중계, 공통기능 추상화 
  API 서버 / 오케스트레이션 - 배포가능한 단위로 분리, 개별서비스를 API형태로 구현 
  데이터베이스 / RDB, SQL, NoSQL - 각 API 서버에서 사용, 다양한 기술기반의 DB
  인프라 및 통신 / REST, JSON - 표준기반 경량 인터페이스, 표준기반 통신규약 
  클라이언트 / Web, Mobile - 클라이언트 어플리케이션, MSA의 API 서비스 소비
MSA vs 모놀리식
  독립성 - 고응집도, 저결합도 &lt;&gt; 서비스간 영향높음
  유지보수 - 용이, 단순 &lt;&gt; 전체의 이해 필요
  확장성 - Scale OUT &lt;&gt; Scale UP
  배포 - 작은배포 &lt;&gt; 한꺼번에 배포
  오류처리 - 단위기능의 오류 &lt;&gt; SPF 단일실패점 전파가능
  기술스택 - 최신기술 다양사용 &lt;&gt; 같은코드 공유, 같은기술
  데이터베이스 - 별도의 DB &lt;&gt; 중앙 DB

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
