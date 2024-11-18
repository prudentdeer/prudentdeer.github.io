---
title: 자원최적화
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 프로젝트관리]
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
      I. 일정과 원가의 트레이드오프, 자원최적화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 자원최적화의 정의
        </div>
        <div class="para-cntnt">
            자원제약조건을 고려하여 일정을 재조정하여 Task 목표량을 준수하기위한 자원최적화 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 자원최적화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 자원최적화의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/자원최적화.png" alt="자원최적화">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 자원최적화의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            특징) 주공정 경로 (Critical Path) 변경가능, 원가절감 가능, 핵심 인력
리소스스무딩 정의 (Resource Smoothing)
  일정제약조건을 고려하여 자원을 균형투입하고 납기를 준수하기 위한 자원최적화 기법
  특징) 주공정 경로 (Critical Path) 변경없음, 원가초과 가능, 비핵심 인력
Resource Leveling vs Resource Smoothing 
  목적 - 자원 수요/공급의 균형유지 &lt;&gt; 균일한 자원 활용
  제약 - 작업시간, 자원간 불균형 &lt;&gt; 주공정의 변화가 없는 조건
  CP - 변경가능 &lt;&gt; 변경없음
  일정 - 지연 가능 &lt;&gt; 일정 준수
  원가 - 절감 가능 &lt;&gt; 원가 초과 가능
  적용사례 - 일정변경 가능한경우 &lt;&gt; 반드시 납기준수할 경우

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
