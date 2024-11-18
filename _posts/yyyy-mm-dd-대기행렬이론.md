---
title: 대기행렬이론
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 알고리즘]
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
      I. 비용 최적화, 대기행렬이론
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 대기행렬이론의 정의
        </div>
        <div class="para-cntnt">
            확률이론을 적용하여 고객의 도착상황에 대응할 수 있는 경제적 규모 결정위한 의사결정기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 대기행렬이론
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 대기행렬이론의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/대기행렬이론.png" alt="대기행렬이론">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 대기행렬이론의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  모집단 
  대기행렬규칙 
  진입포기 
  중도이탈 
  줄바꿈 
유형
  단일채널 단일단계 - 도착 고객들이 단일 대기행렬을 통해 단일 시스템에서 한단계의 서비스
  단일채널 다중단계 - 도착 고객들이 단일 대기행렬을 통해 단일 시스템에서 다중 단계의 서비스
  다중채널 단일단계 - 도착한 고객들이 여러 창구에서 한단계의 서비스
  다중채널 다중단계 - 도착한 고객들이 여러 줄로 서서 여러 단계의 시비스
처리규칙 
  정적 큐
    FSFC - 도착 순서에 따른 순차 처리 / 은행창구, First-Come-First-Served 
    LCFS - 도착 순서의 역순으로 처리 / 엘리베이터, Last-Come-First-Served
  동적 큐
    SIRO - 도착 순서에 상관 없이 임의 대기열, Service in Random Order 
    Priority - 긴급성의 식별 가능한 특성에 따라 우선 순위

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
