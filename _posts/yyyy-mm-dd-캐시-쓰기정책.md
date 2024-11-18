---
title: 캐시 쓰기정책
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
      I. 캐시메모리 쓰기정책
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 캐시 쓰기정책의 정의
        </div>
        <div class="para-cntnt">
            정의 - CPU의 쓰기동작시 캐시메모리와 주기억장치에 동시에 Write 하는 캐시쓰기정책
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 캐시 쓰기정책
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 캐시 쓰기정책의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/캐시-쓰기정책.png" alt="캐시 쓰기정책">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 캐시 쓰기정책의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            일관성 유지 - VI 프로토콜
  장점 - 구조 단순 / 캐시와 주기억장치 일관성 유지
  단점 - 많은 버스트래픽 / 쓰기시간이 길어짐
Write Back 메시백얼
  정의 - CPU의 쓰기동작시 캐시에 쓰고 Swap-Out 시 주기억장치에 복사하는 캐시쓰기정책
  일관성 유지 - MESI 프로토콜
  장점 - 쓰기동작 횟수 최소화, 쓰기시간 단축
  단점 - 일관성 유지 어려움 / 블록교체시 dirty bit 확인필요
캐시 Write Miss 발생시의 정책
  Write Through / No Allocate - Cache Miss시, Main memory의 블록만 수정
  Write Back / Allocate - Cache Miss시, Main memory의 블록을 Cache Memory에 할당해 Cache Memory에 Write

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
