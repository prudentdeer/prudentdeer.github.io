---
title: 체크포인트회복기법
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 데이터베이스]
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
      I. 검사점이용 데이터회복, 체크포인트 회복기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 체크포인트회복기법의 정의
        </div>
        <div class="para-cntnt">
            로그에 체크포인트를 기록하고 장애발생시 이후 트랜잭션만 회복작업 수행하는 회복기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 체크포인트회복기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 체크포인트회복기법의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/체크포인트회복기법.png" alt="체크포인트회복기법">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 체크포인트회복기법의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  검사점 - 변경 내용에 대해 일정 기간 단위로 주기적 체크 포인트 생성
  회복 효율성 - 간결한 검사 회복 시 로그 파일의 정보를 모두 체크할 필요 없음
상세설명
  정상동작 - 트랜잭션 수행 중, 검사점 기반으로 로그 기록 수행
  회복동작 - 
    - 로그 정보를 모두 검사하여 REDO, UNDO 연산을 실행할 트랜잭션과 체크포인트 선정
    - 검사점의 로그 기록을 기반 REDO/UNDO 수행
    - 검사점 이전 시작 트랜잭션은 REDO, 검사점 이후 시작 트랜잭션은 UNDO
  장점 - 검사점에서만 로그 기록으로 운영 효율성 증대
  단점 - 검사점 시점 정의에 따르는 트랜잭션 복구 노력 비용 증가

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
