---
title: 동시성제어병행제어
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
      I. DB 무결성 확보를 위한 동시성 제어
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 동시성제어병행제어의 정의
        </div>
        <div class="para-cntnt">
            DB의 다중사용자 환경에서 트랜잭션들의 직렬성, 일관성, 동시수행 보장하는 병행제어 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 동시성제어병행제어
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 동시성제어병행제어의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/동시성제어병행제어.png" alt="동시성제어병행제어">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 동시성제어병행제어의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          안된경우 문제점 or 필요성 갱현모연 데성일보
  트랜젝션 측면
    갱신내용 손실 - 나중 트랜잭션이 갱신 값을 덮어쓰는 경우 발생
    현황파악 오류 - 트랜잭션의 중간 수행 결과를 다른 트랜잭션이 참조
    모순성 - 복수의 사용자가 동시에 DB를 Access 하여 갱신
    연쇄복귀 불가 - 다른 트랜잭션이 처리한 부분에 대해서는 취소 불가한 상태 발생
  DBMS 측면
    데드락 - 트랜잭션들은 무한히 대기
    성능저하 - 확장성과 처리량에 영향
    일관성 - 예상치 못한 결과가 발생
    보안문제 - 민감한 정보에 대한 무단 액세스 및 변경
제어기법 동이낙타락다
  Locking / 공유락, 전용락 - 자원 상호 배제 제공하는 기법
  2 Phase Locking / 확장, 수축 - 모든 트랜잭션들이 Lock과 Unlock 연산을 확장, 수축 단계로 구분
  Timestamp Ordering / 직렬화, 시스템시계, 논리계수기 - 트랜젝션 직렬화
  낙관적 검증 / 판독, 확인, 기록 - 선반영 후검증
  다중버전 병행제어 / CR Copy, CR block - 하나의 데이터 아이템에 대해 여러 버전의 값 유지
동시성 제어수준 고일저병 언커리시
  0 Level / Read Uncommitted - 갱신중 데이터 읽기허용
  1 Level / Read Committed - 갱신중 데이터 읽기제한
  2 Level / Repeatable Read - 데이터 읽을 때, 종료 시까지 갱신/삭제 제한
  3 Level / Serializable Read - 데이터 영역 순차적 읽을 때, 영역 전체에 접근제한
- 병행제어 수준 높을수록 일관성 증가

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
