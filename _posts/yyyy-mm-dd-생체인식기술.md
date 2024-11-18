---
title: 생체인식기술
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 보안]
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
      I. 신체적 행동적 특징으로 개인식별, 생체인식
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 생체인식기술의 정의
        </div>
        <div class="para-cntnt">
            사용자의 고유한 생체적 특징인 지문, 얼굴 등을 측정, 분석하여 사용자를 식별하는 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 생체인식기술
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 생체인식기술의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/생체인식기술.png" alt="생체인식기술">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 생체인식기술의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          신체적 특징
  지문 - 광학, 정전용량
  얼굴 - 서열기반, 딥러닝
  홍채 - 동적, 멀티모달
  정맥 - 손등, 손목
행동적 특징
  음성 - 패턴매칭, 리뷰어 인증
  걸음걸이 - 가속도계, 비전
  행동인식 - 타이핑, 이동패턴
  서명인식 - 정적, 동적

FAR (False Acceptance Rate): 잘못 허용될 확률. 비인가자가 인가될 확률. 보안성 이슈
FRR (False Rejection Rate): 잘못 거절될 확률. 인가자이지만 거부될 확률. 가용성 이슈
CER (Crossover Error Rate), EER(Equal Error Rate): 교차 오류율
- FAR과 FRR이 일치하는 지점으로, 생체인식 도구의 성능을 측정하는 표준 평가 지점이며 낮을수록 정확함

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
