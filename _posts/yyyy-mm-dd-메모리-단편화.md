---
title: 메모리 단편화
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
      I. 메모리 할당방법에 따라 발생하는 문제, 가상메모리 단편화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 메모리 단편화의 정의
        </div>
        <div class="para-cntnt">
            메모리 상에서 프로그램에 의해 사용되지 못하고 낭비되는 부분적인 공간이 발생하는 현상
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 메모리 단편화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 메모리 단편화의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/메모리-단편화.png" alt="메모리 단편화">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 메모리 단편화의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          해결방안 통압재메 단편화는 슬버
  통합 - 주기억장치 내에 인접해 있는 단편화된 공간을 하나의 공간으로 통합
  압축 - 현재 사용되는 모든 기억 공간을 주기억장치의 한쪽 끝으로 옮김
  재배치 - 모든 작업을 하나의 작업 큐에 넣어서 어느 분할에서도 실행 가능
  메모리 풀 - 메모리를 미리 할당 받고 메모리 풀을 만들어 필요할 때 마다 사용하고 반납
내부단편화
  슬랩할당자 - 공간을 작은 크기로 분할하고 해제하는 동적 메모리 관리 기법 
외부단편화
  버디메모리 - 메모리 할당 위한 메모리 페이지 크기 정렬, 할당

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
