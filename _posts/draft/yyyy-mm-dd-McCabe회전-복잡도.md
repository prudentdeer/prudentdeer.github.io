---
title: McCabe회전 복잡도
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
      I. SW 복잡도 측정기법, McCabe 회전 복잡도
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. McCabe회전 복잡도의 정의
        </div>
        <div class="para-cntnt">
            SW 복잡도를 정량적으로 계산하기 위해 SW 제어 흐름 그래프를 통해 회전수를 계산하는 방법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. McCabe회전 복잡도
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. McCabe회전 복잡도의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/McCabe회전-복잡도.png" alt="McCabe회전 복잡도">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. McCabe회전 복잡도의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  이해용이 : 그래프, 계산식의 폐구간 개수이용
  정적분석 도구 활용 : 복잡한 코드 분석시, 자동화 도구 이용
측정기법 그폐제
  그래프 - edge - node + 2
  폐구간 - 폐구간 + 1
  제어문 - 의사결정수 + 1
측정요소 노에 시와두이
  그래프요소 - node, edge
  제어흐름 - sequence, while, do-while, if-else
척도 (10이하 구성 권장)
  5 이하 - 매우 간단
  5~10 - 매우 구조적, 안정적
  20 이상 - 문장/구조 복잡
  50 이상 - 비구조적, 불안정

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
