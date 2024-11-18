---
title: 뮤테이션 테스트
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
      I. 뮤테이션 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 뮤테이션 테스트의 정의
        </div>
        <div class="para-cntnt">
            의도적으로 소스코드를 변형시키고 뮤턴트 데이터를 실행시켜 테스트하는 결함기반 테스트 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 뮤테이션 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 뮤테이션 테스트의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/뮤테이션-테스트.png" alt="뮤테이션 테스트">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 뮤테이션 테스트의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          프로세스 컴오연테
  컴포넌트 변용 - 컴포넌트 선택,변용, 통합단계 중 Mutation Test를 위한 변용작업 수행
  오류형태 파악 - 검출하고자 하는 오류형태를 파악 (사용자 변용오류, 컴포넌트 자체결함)
  연산자 결정 - 속성변용, 서비스변용,  입력값변용, 출력값변용에 필요한 연산자 결정
  테스트 수행 - 식별된 결함을 피드백하여 컴포넌트의 재변용 및 재시험 실시
구성요소
  소스코드
  뮤턴트 제네레이터
  뮤테이션
  라이브 뮤턴트
  데드 뮤턴트
유형 퓨패스
  Do Fewer / 선택성 - 일부 뮤턴트만 사용하는 샘플링과 선택된 뮤테이션, 연산자에 의한 뮤턴트를 사용하는 선택적 뮤테이션 기법
  Do Faster / 신속성 - 여러 뮤턴트의 동일한 컴파일러를 사용하는 뮤테이션 기법, 여러 뮤턴트를 묶어 하나의 뮤턴트로 생성하는 MSG 기법
  Do Smarter / 분산성 - Test 수행을 여러 기계에 분산 수행함
뮤테이션 테스트와 비버깅 비교
  방법 - 의도적 변형 &lt;&gt; 의도적 오류삽입
  방식 - 뮤턴트 생성 &lt;&gt; 오류코드 생성
  목표 - 신뢰성 확보 &lt;&gt; 잔존오류 추정

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
