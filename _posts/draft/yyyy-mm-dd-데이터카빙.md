---
title: 데이터카빙
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
      I. 컴퓨터 포렌식 데이터 복구 기법, 데이터 카빙
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터카빙의 정의
        </div>
        <div class="para-cntnt">
            파일 시스템의 메타데이터나 디렉토리 구조 없이, 바이너리 레벨에서 데이터를 복구하는 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 데이터카빙
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터카빙의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/데이터카빙.png" alt="데이터카빙">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 데이터카빙의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          중요요소
  카빙 소요시간 - 복구 시 사용하는 검색 알고리즘 및 처리 부분 최적화
  데이터 정확성 - 파일의 특성들을 조합한 적확성 향상
분류 
  연속적 데이터 카빙 - 데이터가 저장매체의 연속된 공간에 저장된 경우 수행하는 기법
  비연속적 데이터 카빙 - 데이터 단편화가 발생하여 저장매체 여러 부분에 조각나 저장된 경우 수행하는 기법
주요기법 헤램파 조시엔
  연속적 
    헤더/푸터 카빙 - 파일 고유의 헤더와 푸터 시그니처 활용
    램슬랙 카빙 - 윈도우 시스템의 램 슬랙이 항상 0x00으로 채워지는 성질 이용
    파일크기 카빙 - 각 파일의 고유한 헤더 구조체를 이용
  비연속적
    파일조각 비율 - 각 파일의 조각난 수에 따라 단편화된 부분을 복구하는 기법
    시그니처 기반 - 각 파일의 시그니처를 기반으로 단편화된 부분을 복구하는 기법
    엔트로피 이용 - 블록/클러스터의 엔트로피를 계산하여 특정 파일의 조각을 분류하는 기법
데이터 카빙과 디스크 이미징 비교
  개념 - 손상된 파일의 복구 &lt;&gt; 데이터 복제 및 보존
  목적 - 특정 파일 데이터 복구 &lt;&gt; 디지털포렌식, 복구, 보안
  작업단위 - 파일, 파일조각 &lt;&gt; 디스크
  저장형식 - 개별파일, 조각 &lt;&gt; 이미지 파일
  작업방식 - 시그니처 및 패턴 분석 &lt;&gt; 비트 수준 복제

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
