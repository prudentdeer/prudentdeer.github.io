---
title: 낙관적 검증
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
      I. 트랜잭션 종료 후 직렬성 검사, 낙관적 검증
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 낙관적 검증의 정의
        </div>
        <div class="para-cntnt">
            트랜잭션 수행 동안은 검사하지 않고, 트랜잭션의 종료 시 일괄적으로 검사하는 동시성제어기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 낙관적 검증
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 낙관적 검증의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/낙관적-검증.png" alt="낙관적 검증">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 낙관적 검증의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          절차설명 판확기 RVE
  판독 단계 (Read Phase) - 모든 갱신은 사본에 수행하고 실제 데이터베이스에 대해서는 수행하지 않음
  확인 단계 (Validation Phase) - 데이터베이스에 반영 전 직렬 가능성 위반여부를 확인
  기록 단계 (Execution Phase) - 확인 단계를 통과하면 트랜잭션의 실행 결과를 데이터베이스에 반영

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
