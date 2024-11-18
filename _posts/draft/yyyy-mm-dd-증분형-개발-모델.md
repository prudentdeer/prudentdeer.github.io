---
title: 증분형 개발 모델
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
      I. 증분형 개발모델
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 증분형 개발 모델의 정의
        </div>
        <div class="para-cntnt">
            SW 개발범위를 여러 증분으로 나누고 병행개발을 통해 증분별 개발 후 통합하는 개발방법론
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 증분형 개발 모델
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 증분형 개발 모델의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/증분형-개발-모델.png" alt="증분형 개발 모델">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 증분형 개발 모델의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  폭포수모델 변형 - 폭포수 모델의 변형으로 증분에 따라 개발하여 통합 
  병행개발 - 개발 그룹 별 증분의 병행 개발을 통해 개발 기간 단축   
  관리복잡 - 증분의 수가 많고 병행 개발이 많아지면 관리가 어려움
증분형과 진화형 비교
  특징 - 병행개발 &lt;&gt; 순차적개발
  적용 - 요구 사항이 명확할 경우 &lt;&gt; 요구사항이 불명확할 경우
  장점 - 점진적 통합으로 후반 통합의 충격 완화 &lt;&gt; 불완전한 요구사항에 대응 가능
  단점 - 다수의 빌드 관리 부담 &lt;&gt; 비용 및 일정 증가 가능성

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
