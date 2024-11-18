---
title: 람다 아키텍처
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 데이터베이스]
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
      I. 듀얼 파이프라인, 람다 아키텍처
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 람다 아키텍처의 정의
        </div>
        <div class="para-cntnt">
            배치, 스피드, 서빙레이어 기반 데이터 처리 파이프라인을 두벌로 설계 데이터분석 아키텍처
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 람다 아키텍처
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 람다 아키텍처의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/람다-아키텍처.png" alt="람다 아키텍처">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 람다 아키텍처의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          상세내용 람배스서
  레이어 구조 – 3개 레이어 구조(배치, 스피드, 서빙)
  아키텍처 목적 – 전송 지연 최소화, 일관성, 정확성 제공
  프로세싱 패러다임 – 배치 + 스트림 조합 (배치 + 실시간)
  재작업 패러다임 – 배치 사이클마다 전체 데이터 재작업
  자원 소비 – 많음 (배치 사이클 마다 재작업)
  신뢰성 – 배치는 신뢰성, 스트림은 근사치 제공

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
