---
title: 모놀리스 > MSA
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
      I. 모놀리스 &gt; MSA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 모놀리스 > MSA의 정의
        </div>
        <div class="para-cntnt">
            모놀리스 - 하나의 시스템으로 구성되어있고 단일 프로세스로 실행되는 시스템 구조
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 모놀리스 > MSA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 모놀리스 > MSA의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/모놀리스-,-MSA.png" alt="모놀리스 > MSA">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 모놀리스 > MSA의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            매크로 - 모놀리스 시스템 안에 각각의 영역을 API 화하여 언제든 서비스별 분리 가능한 구조 (같은 디비 사용)
  미니 - 영역별로 서비스는 분리했으나 일부만 디비까지 분리된 하이브리드형 구조
  마이크로 - 서비스를 여러 개의 작은 마이크로서비스로 구성하고 API 연계하는 폴리글랏형 아키텍처
비교
  독립성 - 낮음 &lt;&gt; 낮음 &lt;&gt; 중간 &lt;&gt; 높음
  배포단위 - 전체 &lt;&gt; 전체 &lt;&gt; 모듈 &lt;&gt; 개별
  확장성 - 수직 &lt;&gt; 수직 &lt;&gt; 수평 &lt;&gt; 수평

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
