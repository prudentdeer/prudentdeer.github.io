---
title: 파이프라인 해저드
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
      I. 파이프라이닝 방해요소, 파이프라인 해저드
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 파이프라인 해저드의 정의
        </div>
        <div class="para-cntnt">
            파이프라인 수행이 지정된 클럭에서 수행되지 못하도록 방해 받는 상태
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 파이프라인 해저드
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 파이프라인 해저드의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/파이프라인-해저드.png" alt="파이프라인 해저드">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 파이프라인 해저드의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 구데제
  구조적해저드 자하인지
    원인 - 자원충돌, 메모리/레지스터 충돌, 폰노이만 아키텍처
    해결 - 자원추가 (병렬구성), 메모리 인터리빙 (HW병렬구성), 하바드 아키텍처 (데이터,명령어분리) ,지연 (NOP)
  데이터해저드 전지비프
    원인 - 명령어 값이 이전 명령어 값에 종속
    종류 - RAW (Read after Write), WAR, WAW
    해결 - 전방전달 (HW추가), 지연 (NOP), 비순차실행(컴파일 실행순서 변경), 프로그래밍 방식 (레지스터 고려)
  제어해저드 분브프
    원인 - 분기 명령어에 의해 발생
    분기 - 결정 시점에 잘못된 명령이 파이프라인에 있기 때문에 발생
    해결 - 분기예측 (정적/동적 예측), 브랜치 지연 (비순차실행), 프로그래밍 방식 (inline 메소드, loop unrolling)

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
