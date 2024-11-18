---
title: 샌드위치 테스트와 빅뱅 테스트
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
      I. 샌드위치 - 상향식과 하향식 테스트의 접근 방식을 결합한 혼합식 통합테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 샌드위치 테스트와 빅뱅 테스트의 정의
        </div>
        <div class="para-cntnt">
          비교
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 샌드위치 테스트와 빅뱅 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 샌드위치 테스트와 빅뱅 테스트의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/샌드위치-테스트와-빅뱅-테스트.png" alt="샌드위치 테스트와 빅뱅 테스트">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 샌드위치 테스트와 빅뱅 테스트의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            사용모듈 - 드라이버, 스텁 모두 사용 &lt;&gt; 모두 미사용
  통합방식 - 점진적 &lt;&gt; 비점진적
  오류발견 - 쉬움 &lt;&gt; 어려움
  수정용이성 - 상대적 쉬움 &lt;&gt; 어려움
  프로젝트규모 - 대규모에 적합 &lt;&gt; 소규모에 적합
  시간 - 병렬테스트가 가능 &lt;&gt; 비용 비용이 많이 듦 상대적 적게 듦
고려사항
  테스트 범위 - 다양한 케이스로 구성하되, 변경이 없도록 명확히 설정 - MECE, 변경관리
  테스트 횟수 - 가능한 반복 수행하는 것이 바람직함 - 최소 3~4회 이상
  테스트 역할 - 이해관계자들의 역할을 구분 지어 효율적으로 수행 - 사용자, 운영자, 관리자

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
