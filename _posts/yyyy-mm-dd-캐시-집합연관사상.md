---
title: 캐시 집합연관사상
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
      I. 직접 사상보다 캐쉬 적중률 향상, 집합연관사상기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 캐시 집합연관사상의 정의
        </div>
        <div class="para-cntnt">
            집합 번호는 같고 태그가 다른 두개 이상의 단어를 저장할 수 있는 구조를 갖는 사상 방식
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 캐시 집합연관사상
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 캐시 집합연관사상의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/캐시-집합연관사상.png" alt="캐시 집합연관사상">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 캐시 집합연관사상의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  메모리 블록 그룹이 하나의 세트 공유
주소형식 테세단
  집합필드 - 태그, 데이터로 이루어진 주소 집합
동작과정
  세트선택 - 메모리 주소 세트 비트 이용 하나 선택
  캐시적중 - 세트 내 태그와 비교, 일치 시 캐시 적중으로 CPU로 인출
  캐시미스 - 불일치 시 캐시 미스로 메모리 접근, 라인들 중 교체할 라인 결정하여 교체
장점 
  직접 사상, 연관 사상 장점 조합
  메모리 블록은 특정 세트 내 어느 곳이나 적재가능
단점 
  복잡성 - 동일한 집합 내의 태그번호로 검색 위한 복잡한 회로 필요

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
