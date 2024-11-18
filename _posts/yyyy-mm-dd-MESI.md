---
title: MESI
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 컴퓨터구조]
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
      I. Write Back 기반 프로토콜, MESI
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MESI의 정의
        </div>
        <div class="para-cntnt">
            멀티프로세서 환경 캐시일관성 유지위해 flag 할당 후 데이터의 유효성 판단하는 프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MESI
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MESI의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MESI.png" alt="MESI">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MESI의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  프로세서가 Cache 데이터 변경해도 주기억장치의 내용은 갱신되지 않음
  변경된 Cache의 스누피 제어기가 변경 사실을 다른 스누피 제어기들에게 통보
프로토콜 MESI
  Modified / 데이터 수정 - 캐시 내 라인 주기억장치와 다름, 그 라인은 캐시에만 존재
  Exclusive / 유일한 사본 - 캐시 내 라인은 주기억장치와 동일, 다른캐시에는 없음
  Shared / 두개이상 공유 - 캐시 내 라인은 주기억장치와 동일, 다른캐시에도 있을 수 있음
  Invalid / 수정된 데이터 - 캐시 내 라인은 유효한 데이터 포함하지 않음
MESI 프로토콜 VI 프로토콜 비교
  기반 - Write back &lt;&gt; Write through
  구성 - M, E, S, I &lt;&gt; Valid, Invalid
  Flag - 사용 &lt;&gt; 미사용
  유형 - MOSI, MOESI &lt;&gt; VI-R, VI-S

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
