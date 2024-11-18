---
title: 파일구조
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 자료구조]
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
      I. 파일 내 레코드 편성 배열방법, 파일구조
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 파일구조의 정의
        </div>
        <div class="para-cntnt">
            파일을 구성하는 레코드들이 보조기억장치에 순차, 직접, 색인순차 방법으로 기록되는 자료구조
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 파일구조
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 파일구조의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/파일구조.png" alt="파일구조">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 파일구조의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 파순직색
  순차파일 / 연속공간 - 논리적 처리순서에 따라 연속된 저장공간에 기록
    장점 - 메모리효율, 빠른엑세스
    단점 - 검색속도 느림, 자료이동 빈번
  직접파일 / 해시함수 - 해시함수 키 이용해 직접 주소로 접근 
    장점 - 삽입삭제 용이, 기록순서 미제약 
    단점 - 메모리낭비, 공간효율 저하
  색인순차파일 / 인덱스 - 키순 정렬하여 기록, 키 인덱스 편성
    장점 - 효율적 검색, 순차-임의처리 병행
    단점 - 기억공간 필요, 파일 재편성 필요
고려사항
  자료측면
    파일저장매체 특성 - 디스크, 자기테이프 등 고려
    매체 접근형태 - 순차, 직접, 색인 방식 고려
  성능측면
    파일연산 유형 - 파일 읽기, 쓰기 연산고려
    사용자 응답시간 - 파일활동 비율 계산

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
