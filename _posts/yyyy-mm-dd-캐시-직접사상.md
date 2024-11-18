---
title: 캐시 직접사상
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
      I. 주기억장치 블록을 지정. 직접사상기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 캐시 직접사상의 정의
        </div>
        <div class="para-cntnt">
            주기억장치의 블록이 캐시 특정라인에 적재, 적중여부는 블록이 적재될 라인만 검사하는 사상기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 캐시 직접사상
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 캐시 직접사상의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/캐시-직접사상.png" alt="캐시 직접사상">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 캐시 직접사상의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  모듈로 연산 : 주기억 장치의 블록 j 가 적재될 수 있는 캐시 슬롯의 번호 i는 모듈로 연산에 의해 결정
주소형식 태라단
  태그 필드 - 태그 번호
  라인 필드 - 캐시 라인 중 하나를 지정
  단어 필드 - 각 블록 내 단어 중 하나 구분
동작과정
  캐시라인 선택 - 캐시로 메모리 주소 전달 시 s 비트의 라인번호 기반 캐시 라인 선택
  캐시적중 - 일치 시 단어 필드 라인 내 단어 인출
  캐시미스 - 라인 적재 후 주소 태그를 라인에 기록, 해당 라인에 다른 블록 존재 시 삭제
장점
  단순 - 사상과정이 간단(교체 알고리즘 불필요)
  저비용 - 작은 용량의 RAM을 캐시 기억장치로 사용
단점 
  실패율 높음 - 동일 라인에 적재되는 두 블록 반복접근시

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
