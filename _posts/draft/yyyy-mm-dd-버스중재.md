---
title: 버스중재
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
      I. 시스템 버스의 효율적 사용, 버스중재
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 버스중재의 정의
        </div>
        <div class="para-cntnt">
            버스경합 발생시, 버스 마스터가 기준에 따라 순서대로 버스를 사용할 수 있게 해주는 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 버스중재
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 버스중재의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/버스중재.png" alt="버스중재">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 버스중재의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 직병폴
  직렬중재 - 모든 버스 마스터들이 직렬로 연결되어 "데이지 체인"형태
  병렬중재 - 독립적으로 버스 사용 요구/사용 승인 신호 사용
  폴링 - 버스 중재기가 각 마스터들이 사용을 원하는지 주기적 검사하여 버스 승인여부 결정
직렬, 병렬, 폴링방식 비교
  장점 - 구현간단 &lt;&gt; 빠른처리 &lt;&gt; 충돌회피
  단점 - 단일실패점 &lt;&gt; 설계복잡 &lt;&gt; 시간지연
  예시 - 직렬통신장치 &lt;&gt; 메모리 모듈, 버스 &lt;&gt; 입출력 장치
- 다수의 디바이스가 하나의 버스를 공유하는 환경에서 중요한 역할

  BREQ - 버스 마스터가 시스템 버스에 사용권한을 요청
  BGNT - 시스템 버스가 CPU로부터 버스 사용권한을 허가 받아 버스 사용권한을 승인
  BBUSY - 이미 사용중인 버스를 다른 버스 마스터가 사용하려고 할 때 사용중이라는 신호
https://pololove.tistory.com/75
https://blog.skby.net/%EB%B2%84%EC%8A%A4-%EC%A4%91%EC%9E%AC-bus-arbitration/

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
