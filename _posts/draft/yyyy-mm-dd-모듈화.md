---
title: 모듈화
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
      I. 소프트웨어 설계원리, 모듈화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 모듈화의 정의
        </div>
        <div class="para-cntnt">
            유지보수성 극대화를 위해 시스템을 분해하고 추상화를 통해 모듈을 분리하는 설계, 구현기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 모듈화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 모듈화의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/모듈화.png" alt="모듈화">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 모듈화의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          필요성
  복잡도 감소 / 유지보수 용이 / 비용 감소
특성
  모듈성 - 최적의 프로그램 단위 / 성능향상, 컴포넌트화, 재 사용성
  응집도 - 모듈의 독립성을 나타내는 개념 / 높을수록 좋음
  결합도 - 모듈간 연관성을 측정하는 척도/ 낮을수록 좋음
FAN IN 인재아불
  자신을 사용하는 모듈의 개수로, 재사용성 설계를 위한 지표
FAN OUT
  자신이 호출하는 모듈의 개수로, 불필요 모듈 호출파악 지표
- FAN IN을 높게, FAN OUT 낮게 최적화

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
