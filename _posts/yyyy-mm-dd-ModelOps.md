---
title: ModelOps
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 인공지능]
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
      I. 거버넌스와 생명주기의 효율적 관리, ModelOps
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ModelOps의 정의
        </div>
        <div class="para-cntnt">
            모델의 거버넌스와 생명주기 관리위해 빌드, 관리, 배포, 모니터링 지원 자동화 방법론
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. ModelOps
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ModelOps의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/ModelOps.png" alt="ModelOps">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. ModelOps의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          프로세스 빌매디모
  Build / 데이터관리, 개인정보 - 데이터를 수집하고 모델 학습을 위한 준비
  Manage / 버전관리, 테스트 - 데이터를 이용해 모델 학습, 테스트, 버전 관리 및 승인
  Delploy / 스케일링, 통합 - 모델을 배포하고 비즈니스 환경에 통합, 모델 사용
  Monitor / 로깅, 예외처리 - 지속적으로 모니터링하고 모델 업데이트, 개선
모델옵스 필요한 상황 병요버블
  병목현상 - 모델 개발과 배포사이의 병목현상 발생시
  블랙박스 모델 - 모델배포 관련된 정보, 작동원리를 알지 못할때
  요구대응 - 요구사항 변경시 변화속도를 따라가지 못할때
  버전관리 문제 - 어떤 버전에 어떤 결과인지 버전관리가 어려울때
- 모델옵스통해 데이터 드리프트 예방 필요
기계학습 &gt; 드리프트 관리 / 자동화 &gt; 모델옵스

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
