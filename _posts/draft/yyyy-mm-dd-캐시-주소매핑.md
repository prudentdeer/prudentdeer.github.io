---
title: 캐시 주소매핑
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
      I. 캐시 주소매핑
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 캐시 주소매핑의 정의
        </div>
        <div class="para-cntnt">
            캐시의 고속처리를 위해 캐시에 메인메모리의 주소를 태그, 라인, 단어로 저장하는 기법 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 캐시 주소매핑
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 캐시 주소매핑의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/캐시-주소매핑.png" alt="캐시 주소매핑">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 캐시 주소매핑의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          필요이유 일효페가
  캐시일관성 보장 - 메인 메모리와 캐시의 데이터 불일치 방지
  캐시효율성 보장 - 특정 주소에 대한 캐시 액세스를 효율적으로 지원
  페이지테이블 사용 - 가상주소를 빠르게 물리주소로 변환
  가상메모리 관리 - 가상메모리와 물리 메모리간 액세스 지원
주소맵핑 방식 직연집 태라단 태단 태세단
  직접사상 - 주기억장치의 블록이 캐시 지정 라인에만 적재
  연관사상 - 주기억장치의 블록을 캐시 어느 라인이든 적재
  집합연관사상 - 두개 이상의 단어를 저장할 수 있는 구조를 갖는 사상 방식

  캐시 메모리는 메인 메모리에 비해 크기가 매우 작기 때문에 메인 메모리와 1:1로 매칭하는 것은 불가능하다. 또한 캐시가 아무리 CPU에 가깝게 위치하더라도, 데이터가 캐시 내의 어느 곳에 저장되어 있는지 찾기가 어려워 모든 데이터를 순회해야 한다면 캐시의 장점이 사라지게 된다.
따라서, 캐시에 데이터를 저장할 때 이를 쉽게 찾을 수 있도록 특정 자료 구조를 사용하여 묶음으로 저장하며, 이를 캐싱 라인(Caching Line)이라고 한다. 빈번하게 사용되는 데이터의 주소들이 흩어져 있기 때문에 캐시에 저장하는 데이터에는 데이터의 주소 등을 기록해둔 태그를 달아둘 필요가 있는데, 이러한 태그들의 묶음을 의미하는 것이다.
간단히 캐시 메모리에 주소를 저장하는 방식을 말하는 것으로 이해해도 무방하며, 일반적으로 세 가지 매핑 방식으로 구분할 수 있다

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
