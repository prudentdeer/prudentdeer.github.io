---
title: 유즈케이스다이어그램
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
      I. 사용자 입장의 표현, 유즈케이스 다이어그램
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 유즈케이스다이어그램의 정의
        </div>
        <div class="para-cntnt">
            시스템이 제공하고 있는 기능 및 관련된 외부요소를 사용자의 관점에서 표현하는 동적 다이어그램
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 유즈케이스다이어그램
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 유즈케이스다이어그램의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/유즈케이스다이어그램.png" alt="유즈케이스다이어그램">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 유즈케이스다이어그램의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  기본구성 유액시관
    Usecase - 시스템이 제공해야 하는 서비스, Actor가 시스템을 통한 일련의 행위
    Actor (행위자) - 사용자가 시스템에 대해 수행하는 역할, 시스템과 상호작용하는 사람 또는 사물
    시스템 (System) - 전체시스템의 영역을 표현, 특별한 의미를 가지지 못함
    관계
  관계표현 연확포일그
    연관 관계 - 방향성 없는 실선표기, 상호인지
    확장의존 관계 - 클래스 변화가 타클래스 영향, 선택적 확장하는 관계
    포함의존 관계 - 클래스 변화가 타클래스 영향, 반드시 포함하는 관계
    일반화 관계 - 자식이 부모속성 물려받음, 상속
    그룹화 - 여러개의 Usecase 단순화
시나리오 작성 명개우액 선후이비
  유즈케이스명 - 상품등록
  개요 - 
  우선순위 - 1, 중요도 상
  액터 - 관리자
  선행조건 - 관리자는 권한아이디 로그인, 상품관리
  후행조건 - 신규 상품정보 저장
  이벤트 흐름 - 
  비기능 요구사항 - 없음

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
