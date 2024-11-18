---
title: 통합 테스트
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
      I. 모듈통합 테스트, 통합 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 통합 테스트의 정의
        </div>
        <div class="para-cntnt">
            애플리케이션의 모든 구성 모듈을 통합시 예상대로 상호작용하는지 확인하는 테스트
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 통합 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 통합 테스트의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/통합-테스트.png" alt="통합 테스트">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 통합 테스트의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 상하점비
  테스트 유형
    비점진적 통합 - 모든 컴포넌트를 사전에 통합하여 한꺼번에 테스트하는 방법
      - 규모작은 SW유리, 단시간 가능, 장애위치 파악 어려움
    점진적 통합 - 모듈 단위로 단계적으로 통합하며 테스트하는 방법
      - 오류수정 용이, 인터페이스 연관오류 해결
      - 점진적 통합 방식은 상향식 및 하향식 통합방식으로 테스트가 가능
  테스트 방향
    하향식 통합 - 메인프로그램부터 아래 방향으로 제어의 경로를 따라 하향식으로 통합 테스트
      - 주요 제어모듈 기준
      - 깊이 우선 통합법, 넓이 우선 통합법 사용
      - 테스트 스텁 사용
    상향식 통합 - 최하위 레벨의 모듈부터 위쪽 방향으로 제어의 경로를 따라 이동하면서 테스트
      - 클러스터 필요, 하나의 주요 제어 모듈과 관련된 종속 모듈의 그룹
      - 테스트 드라이버 사용
- 상향식과 하향식 통합테스트시, 테스트 드라이버와 테스트 스텁이 더미 모듈 역할 수행

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
