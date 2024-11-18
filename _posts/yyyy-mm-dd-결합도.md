---
title: 결합도
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
      I. Loosly Coupled 지향, 결합도
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 결합도의 정의
        </div>
        <div class="para-cntnt">
            소프트웨어 개발시 Loosly Coupled 위해 2개이상 모듈간 상호의존성 평가 척도
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 결합도
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 결합도의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/결합도.png" alt="결합도">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 결합도의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          결합도 단계 내공외제스자 - 낮을수록 좋음
  내용 - 한 모듈이 다른 모듈의 내부 자료나 제어정보를 사용
  공통 - 많은 모듈들이 전역변수를 참조할 때 발생
  외부 - 모듈들이 소프트웨어의 외부 환경과 연관되는 경우
  제어 - 한 모듈이 다른모듈 논리제어
  스템프 - 모듈 사이에 구조체로 자료구조 교환
  자료 [제일좋음] - 모듈들이 간단히 변수를 파라미터로 교환
결합도 낮추는 기법 엠소디디
  아키텍처
    MSA / 폴리글랏
    SOA / 서비스조합
  개발방법
    DI / 의존성주입
    디자인패턴 / 생성, 구조, 행위
- 반대개념 응집도는 높을수록 좋음

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
