---
title: 경쟁조건
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 운영체제]
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
      I. 자원경쟁, 레이스 컨디션
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 경쟁조건의 정의
        </div>
        <div class="para-cntnt">
            멀티 프로세스가 공유 메모리에 동시에 접근을 시도해, 메모리 일관성 보장이 어려운 상태
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 경쟁조건
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 경쟁조건의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/경쟁조건.png" alt="경쟁조건">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 경쟁조건의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          문제점 권데예재
  보안 / 권한상승 공격 - 공격자가 권한취득 악용가능
  자원 / 데이터 손상 - 데이터의 일관성 손실
  시스템 / 예측불가 동작 - 예측불가능 오작동
             / 재현불가 동작 - 정해진 패턴이 없음
- 레이스 컨디션을 악용하면 권한상승 악용 공격으로 적용 가능
해결방법 테스인 데피램 뮤세스모
  하드웨어
    Test &amp; Set - 단일 word 검사, 변경수행
    Swap - 다중 word 내용 원자적 교환
    인터럽트 금지 - 임계영역 실행완료까지 차단
  소프트웨어
    데커 알고리즘 - 공유변수와 순서 설정 / 나먼저 쓰고 양보할께 
    피터슨 알고리즘 - 의사표시 및 순서양보 가능 / 너먼저써 난 다음에쓸게
    램포트 알고리즘 - 분산처리 환경 상호배제 / 번호표 순서대로 쓰자

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
