---
title: 데이터 독립성
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
      I. ANSI/X3/SPARC, 데이터 독립성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 독립성의 정의
        </div>
        <div class="para-cntnt">
            데이터의 논리적, 물리적 구조가 변경되더라도 응용프로그램이 영향받지않는 데이터베이스 성질
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 데이터 독립성
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 독립성의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/데이터-독립성.png" alt="데이터 독립성">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 데이터 독립성의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 스독사 외개내 논물 논물
  스키마
    외부 스키마 - 각각의 사용자가 보는 개인적인 DB 스키마
    개념 스키마 - DB에 저장되는 데이터와 그들간의 관계 표현
    내부 스키마 - 물리적 장치에서 데이터가 실제 저장되는 방법 표현
  독립성
    논리적 독립성 - 개념 - 외부 스키마의 변경은 서로 영향 없음
    물리적 독립성 - 내부 - 개념 스키마의 변경은 서로 영향 없음
  사상
    논리적 사상 - 인터페이스와 개념스키마 매핑
    물리적 사상 - 개념스키마와 물리구조 매핑
독립성 적용시 효과 효유업프
  관리측면
    효율성 - 요구사항 유연 대응
    유지보수성 - 유지보수성 향상  
  비즈니스 측면 
    업무 통합화 - 각 업무별 공통 부분 통합
    프로세스 개선 - 업무처리 프로세스 개선
ANSI/X3/SPARC 의 정의
  데이터베이스의 복잡한 구조를 단순화하고, 독립성 보장을 위해 관점을 기준으로 3계층 분리한 구조

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
