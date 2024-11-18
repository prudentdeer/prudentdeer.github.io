---
title: SAST
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
      I. 정적 보안 테스트, SAST
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SAST의 정의
        </div>
        <div class="para-cntnt">
            소스 코드를 통계적으로 검사하여 취약점을 포함하는 소스를 탐지하는 정적 테스트 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SAST
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SAST의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SAST.png" alt="SAST">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SAST의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          장점
  조기취약점 발견 - 개발 초기 단계에서 보안 취약점 발견 가능
  높은 ROI - 프로세스 초기에 수행되므로 수정 비용 적음
  자동화 가능 - CI/CD, DevSecOps 등 지속적 통합에 효과적
단점
  호출확인 제한 - 대부분의 매개변수 값이나 호출 확인 불가능
  False Negative - False Negative가 발생하며 이로 인한 보안 문제 야기
  제한적 커버리지 - 외부에서 발생하는 보안 문제 등 전체적인 취약점 식별 한계

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
