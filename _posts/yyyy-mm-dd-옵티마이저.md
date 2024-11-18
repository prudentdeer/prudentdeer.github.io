---
title: 옵티마이저
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
      I. 최소비용 최적성능 구현, 옵티마이저
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 옵티마이저의 정의
        </div>
        <div class="para-cntnt">
            SQL문의 최적성능 실행계획 수립위해 Rule, Cost 기반 최소비용을 추정하는 DBMS 핵심엔진
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 옵티마이저
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 옵티마이저의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/옵티마이저.png" alt="옵티마이저">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 옵티마이저의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          수행절차 PROGER 프로저
  Parse - SQL 문장 개별 구성요소 파악 / 파싱 트리 생성 / 오류검사
  Query Rewrite - 
  Query Optimization / RBO, CBO - 표준형태로 변환 / 비용 산정 / 계획 생성
  QEP Generation / 포맷 변환 - 실행 가능한 코드로 포맷 변경
  Execution
  Results
유형 인순경 통코비
  RBO - 정해진 규칙 기반으로 실행계획 예측
    인덱스 구조 / 순위기반 / 최적경로
  CBO - 통계, 비용 기반으로 실행계획 가변분석
    통계 사용 / Cost 기반 / 최적비용
옵티마이저와 힌트 비교
  역할 - 실행계획 결정 &lt;&gt; 실행계획 강제
  종류 - RBO, CBO &lt;&gt; DBMS 마다 다름
  사용방법 - 자동으로 선택 &lt;&gt; 명시적 추가
  성능튜닝 - 자동 최적화 기능 &lt;&gt; 개발자가 직접 제어하여 성능 튜닝
  유지보수성 - DBMS의 업데이트 및 버전 따라 변경 &lt;&gt; 개발자가 쿼리에 직접 추가

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
