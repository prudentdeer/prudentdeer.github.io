---
title: 임베디드 시스템 테스트
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 소프트웨어공학]
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
      I. 임베디드 소프트웨어 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 임베디드 시스템 테스트의 정의
        </div>
        <div class="para-cntnt">
            임베디드시스템 구동 소프트웨어의 특수성, 제약조건 고려하여 결함발견을 위한 테스트
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 임베디드 시스템 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 임베디드 시스템 테스트의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/임베디드-시스템-테스트.png" alt="임베디드 시스템 테스트">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 임베디드 시스템 테스트의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          테스트모델 데멀
  Dess-V - 상위통합, 하위 상세검증, SW HW 연계
  Multiple V-model - 프로토타이핑 통한 V 모델 반복
테스트 기법 시구지상 모체
  정적
    시나리오기반 - 외부 입력 사건별로 시나리오를 기술
    구문분석 - 구문분석 통해 결함발생 가능 부분 도출
  동적
    GUI - 이벤트흐름 그래프와 이벤트 시퀀스 작성
    상태전이 - 상태전이 기반 테스트케이스, 전이트리 작성
  확장
    모니터링 - 하드웨어 수정없이 디버깅 및 테스트 제공
    체킹 - 모니터에 추가적인 기능을 넣어 테스트 확장
특성에 따른 고려사항 환의자조
  테스트조건
    환경다양성 - 프로그래밍언어, 컴파일러, 운영체제 다름
    HW 의존 - 다양한 인터페이스 디바이스 
  테스트환경
    자원제약 - 테스트위한 CPU, 메모리의 제약
    낮은조작성 - UI가 없거나 불편한 환경
- 고신뢰성을 요구하기 때문에 엄격한 테스트 필요
https://www.sol-link.com/board/bbs/board.php?bo_table=pds&amp;wr_id=2

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
