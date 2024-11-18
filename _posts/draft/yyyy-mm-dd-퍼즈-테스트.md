---
title: 퍼즈 테스트
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
      I. 잠재적 취약점 식별, 퍼즈테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 퍼즈 테스트의 정의
        </div>
        <div class="para-cntnt">
            무작위 데이터 입력으로 실패를 유발시켜 오류를 분석하고 취약점을 찾아내는 Black Box 테스트
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 퍼즈 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 퍼즈 테스트의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/퍼즈-테스트.png" alt="퍼즈 테스트">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 퍼즈 테스트의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  입력값 무작위, 간단한 신뢰기준, 고수준 자동화
상세설명 대입퍼프 모분
  분석
    대상 프로그램 분석 - 프로그램 실행에 필요한 권한이나 네트워크 사용 여부 등을 분석
    입력 값 분석 - 공격에 활용할 수 있는 데이터를 식별, 파일, 레지스트리, 네트워크 패킷, 환경 변수 등 
  생성 및 실행
    퍼즈 데이터 생성 - 앞 단계의 분석 결과를 활용하여 실제 테스트 데이터 생성
    프로그램 실행 - 퍼즈 데이터를 이용하여 프로그램 실행
  예외처리
    예외 모니터링 - 다양한 예외 상황에 대한 모니터링, 프로세스 종료, 접근 위반 모니터링 등
    예외 분석 - 예외 모니터링 정보를 분석하여 해당 예외가 익스플로잇 가능 여부 판단
유형 블화그
  블랙박스 퍼징 - 사전 지식 없이 퍼징 진행, 퍼징이 신속하게 진행되지만 코드 커버리지가 낮은 단점
  화이트박스 퍼징 - 소스코드를 가지고 있는 상태에서 입력되는 값 형태를 분석하여 퍼징 진행, 신속한 적용이 어려운 단점
  그레이박스 퍼징 - 소스코드는 가지고 있지 않으나 어느정도 파악하여 바이너리에 입력되는 입력값의 형태를 알고 있을 때 사용

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
