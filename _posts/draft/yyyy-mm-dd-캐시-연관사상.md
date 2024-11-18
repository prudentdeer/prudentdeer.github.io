---
title: 캐시 연관사상
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
      I. 장치간의 속도 차이 극복을 위한 연관사상기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 캐시 연관사상의 정의
        </div>
        <div class="para-cntnt">
            직접사상 단점 보완하여 주기억장치의 블록을 캐시의 어느 라인이든 적재할 수 있는 사상기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 캐시 연관사상
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 캐시 연관사상의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/캐시-연관사상.png" alt="캐시 연관사상">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 캐시 연관사상의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징 
  효율성 : 메모리 블록 적재 시 캐시 라인이 정해지지 않음
주소형식 태단
  태그 필드 - 태그 번호
  단어 필드 - 각 블록 내 단어 중 하나 구분
동작과정
  캐시적중 - 메모리 블록은 캐시의 아무 블록 적재, 태그 필드 내용 비교, 일치 시 전송
  캐시미스 - 태그 값 불일치 시 캐시 미스 발생, 메모리로부터 데이터 인출
장점 
  신규 적재 시 캐시 라인 선택 자유, 적중률 향상
단점 
  H/W 구조 복잡, 구현비용 고가

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
