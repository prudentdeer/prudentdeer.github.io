---
title: 응집도
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
      I. High Cohesion 지향, 응집도
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 응집도의 정의
        </div>
        <div class="para-cntnt">
            모듈에 포함된 내부 요소들이 하나의 책임, 목적을 위해 연결되어 있는 응집정도
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 응집도
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 응집도의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/응집도.png" alt="응집도">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 응집도의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          응집도 단계 우논시절통순기 - 높을수록 좋음
  우연적 - 아무 관련성 없는 작업을 한 모듈에서 모음&nbsp;
  논리적 - 유사한 성격의 작업들을 모음
  시간적 - 같은 시간대에 처리 되어야하는 것들을 모음
  절차적 - 모듈 진행 요소들이 서로 관계 되어지고 순서대로 진행
  통신적 - 동일한 입, 출력 자료를 이용하여 서로 다른 기능을 수행하는 기능
  순차적 - 작업의 결과가 다른 모듈의 입력 자료로 사용
  기능적 [제일좋음] - 하나의 기능만 수행하는 모듈
응집도, 결합도 비교
  정의 - 모듈내 응집 &lt;&gt; 모듈간 상호의존성
  목표 - High Cohesion &lt;&gt; Loosly Coupled 
  영향 - 유지보수성, 재사용 &lt;&gt; 유연성, 확장성
- FAN IN 높게, FAN OUT 낮게

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
