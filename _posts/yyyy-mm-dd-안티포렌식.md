---
title: 안티포렌식
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 보안]
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
      I. 사이버 범죄의 은닉 및 삭제 기술, Anti-Forensics
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 안티포렌식의 정의
        </div>
        <div class="para-cntnt">
            디지털 포렌식 대응하여 자신에게 불리하게 작용할 가능성이 있는 증거물을 훼손, 차단하는 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 안티포렌식
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 안티포렌식의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/안티포렌식.png" alt="안티포렌식">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 안티포렌식의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          배경
  포렌식 발전, 익명성, 암호기술 발전
기술 와디로디 압물문스
  HW
    와이핑 - 하드디스크 기존 데이터 완벽 제거, 모든 섹터 null
    디가우징 - 하드디스크 등에 강력한 자기장 노출, 기록 파괴, 복구 불가능장비,
    Log data 삭제 - OS 자동 생성 정보 즉시 자동 삭제
    디스크 덮어쓰기 - 삭제후 디스크에 남은 부분 복구 회피
  SW
    압축파일 암호화 - zip, rar
    문서파일 암호화 - MS오피스, 한글
    물리적 암호화 - 가상디스크, USB, OS
    스테가노그래피 - 이미지,오디오 파일과 같은 디지털 매체를 통해 메시지 은닉 전송
안티안티 포렌식 인비메이 슬스부딕
  데이터수집
    인덱스탐지 - 모든파일 스캔후 탐색
    BitWise - 디스크섹터, 슬랙공간 비할당영역 검색
    메모리덤프 - 메모리상의 데이터 획득
    디스크이미징 - 디스크 원본 복제
  데이터분석
    슬랙공간 - 미할당 영역, 파일헤더 재구성하여 파일복구
    스왑영역 - 메모리 캐시데이터, 라우팅, 프로세스 정보검색
    BruteForce - 패스워드 대입 분석
    Dictionary Attack - 높은 가능성을 지니고 사용되는 단어이용 모든 패스워드를 체계적으로 찾음

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
