---
title: 재공학 (Re)
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
      I. 재사용성 확보 기술, 재공학
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 재공학 (Re)의 정의
        </div>
        <div class="para-cntnt">
            역공학이나 재구조화 후, 다시 순공학을 이용하여 새로 구현함으로 재사용성을 확보하는 방법 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 재공학 (Re)
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 재공학 (Re)의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/재공학-(Re).png" alt="재공학 (Re)">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 재공학 (Re)의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          주요기법 재구모의
  재구조화 - SW 부품을 라이브러리에 모아놓고 새로운 SW 개발에 필요한 부품 결합
  재모듈화 - 시스템의 모듈 구조 변경, 클러스터 분석 및 결합도와 관련
  의미추출 - 코드 수준이 아닌 문서 수준의 복구 방법
리팩토링 vs 리엔지니어링 
  개념 - 모듈의 정제 &lt;&gt; 시스템 개선
  반복성 - 반복 많음 &lt;&gt; 반복이 거의 없음     
  적용범위 - 클래스, 모듈 등 소단위 &lt;&gt; 시스템, 기능 등 대단위     
  적용사례 - 특정 메소드의 이름 변경 &lt;&gt; 시스템의 전반적 모듈화

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
