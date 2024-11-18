---
title: 테스트 원리
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
      I. 원리 결초집 불정살오
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 테스트 원리의 정의
        </div>
        <div class="para-cntnt">
            초기집중 - 개발 설계 시부터 테스트 고려, 결함의 조기 발견 및 재 유입 방지 / 품질 비용 감소
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 테스트 원리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 테스트 원리의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/테스트-원리.png" alt="테스트 원리">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 테스트 원리의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            결함집중 - 결함의 80%는 20%의 특정 모듈에 집중 / 파레토 법칙 
  불완전 - 완벽한 Testing은 불가능 / 자원의 한계
  정황의존 테스트 - 주변 환경에 의한 영향을 받음 / 외부요소, 심리요소
  살충제 패러독스 - 동일한 테스트 전략, 기법을 사용할 시 내성이 생김 / 개발자의 TEST 회피
  오류-부재의 궤변 - 결함이 없어도, 요구사항 충족시키지 못한다면 품질이 낮음 / 테스터의 수동적 자세

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
