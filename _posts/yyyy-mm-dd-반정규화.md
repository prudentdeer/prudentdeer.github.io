---
title: 반정규화
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
      I. 성능향상을 위한 중복허용, 반정규화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 반정규화의 정의
        </div>
        <div class="para-cntnt">
            정규화로 분해된 테이블, 컬럼등을 성능향상을 목적으로 중복을 허용하여 재통합하는 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 반정규화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 반정규화의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/반정규화.png" alt="반정규화">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 반정규화의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          필요성
  검색 성능 향상 - 정규화로 분해된 테이블 간 Join 증가로 검색 성능 저하
  모델링 이해 증대 - 분해된 테이블 간 복잡한 릴레이션으로 모델링 이해의 어려움
  개발 생산성 증대 - SQL 개발 시 해당 테이블의 잦은 조인으로 개발 생산성 저하
절차 대다반
  반정규화 대상조사 - 범위 처리 빈도수 조사, 대량의 범위 처리 조사, 통계성 프로세스 조사, 테이블 조인 개수
  다른방법 유도 - 뷰 테이블, 클러스터링 적용, 인텍스의 조정, 응용 어플리케이션
  반정규화 적용 - 테이블 반정규화, 속성의 반정규화, 관계의 반정규화
주요기법 병분추 중계이
  테이블 레벨
    테이블 병합 - 1:1 병합, 1:N 테이블 병합 (Join 수 감소), Sub-type 끼리 테이블 병합, 코드 테이블 병합
    테이블 분할 - 테이블 수직 분할, 테이블 수평 분할
    테이블 추가 - 통계 테이블 추가, 이력 테이블 추가, 중복 테이블 추가, 부분 테이블 추가 등
  컬럼 레벨
    중복컬럼 추가 - 갱신보다 조회 성능 더 중요하면 양쪽 테이블에 중복 저장
    계산컬럼 추가 - 여러 테이블 조인 후 계산이 필요한 경우 계산 결과 컬럼 추가
    이력컬럼 추가 - 변경 이력, 발생 이력 정보 위한 최신 정보 컬럼 추가

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
