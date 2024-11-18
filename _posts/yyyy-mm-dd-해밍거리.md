---
title: 해밍거리
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 네트워크]
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
      I. 해밍코드 구현위한, 해밍거리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 해밍거리의 정의
        </div>
        <div class="para-cntnt">
            송신, 수신간 데이터의 오류검출, 정정 위해 XOR연산 이용 데이터 유사도를 수치화하는 거리
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 해밍거리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 해밍거리의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/해밍거리.png" alt="해밍거리">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 해밍거리의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          해밍거리 계산 검정
  오류검출 = d MIN = m + 1 (d비트의 오류검출 가능한 해밍거리)
    00 - 0 (오류없음)
    11 - 1 (오류없음)
    01, 10 - 오류 검출
  오류정정 = d MIN = 2m + 1 (d비트의 오류정정 가능한 거리)
    000 - 오류없음
    111 - 오류없음
    110 - 3번째비트 1로 정정
    011 - 1번째비트 1로 정정
- 해밍거리는 AI 유사도측정 협업필터링, 전진오류수정, 해밍코드 구현 시 사용

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
