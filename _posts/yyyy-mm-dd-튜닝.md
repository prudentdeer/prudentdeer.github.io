---
title: 튜닝
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
      I. Business Agility 수행을 위한 DB 튜닝
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 튜닝의 정의
        </div>
        <div class="para-cntnt">
            최적자원으로 최고성능을 얻기위해 설계, 데이터베이스, SQL 조정통한 DB 성능 개선작업
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 튜닝
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 튜닝의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/튜닝.png" alt="튜닝">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 튜닝의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          튜닝 지표, 목적 능시응로 유효사비
  정량적
    처리능력 (Throughput) - 작업을 수행하기 위해서 소요되는 시간을 의미
    처리시간 (Throughput Time) - 작업이 완료되는데 소요되는 시간을 의미
    응답시간 (Response Time) - 사용자가 키를 누른 때부터 시스템이 응답할 때까지의 시간 
    로드시간 (Load Time) - 정기적, 비정기적 발생되는 데이터를 로드 하는 작업
  정성적 - 유지보수성, 운영효율성, 사용자 경험, 비용절감
튜닝영역 설디스 분통정반인키샤파 씨메캐오네 옵힌조
  설계 관점 - DB의 논리적 구조에 대한 성능 개선 작업 / 테이블 분할, 통합, 반정규화, 분산 파일 배치 / 인덱스 / 키 지정
  DBMS 관점 - DB의 메모리 영역, 물리적 구조 등 개선하는 작업 / CPU, 메모리, Cache 크기, OS, 네트워크 환경
  SQL 관점 - SQL문 분석을 통해 성능을 발휘할 수 있도록 조율하는 작업 / 옵티마이저, 힌트, Hash, Join
튜닝절차 성분튜결
  성능진단 - 사용자 인터뷰, 설계, 시스템 구성, 자원사용현황, SQL TRACE
  분석단계 - 설계내용, SQL, DBMS, OS, HW
  튜닝단계 
  결과단계 - 튜닝 후 자료수집/분석, 튜닝결과평가, 산출물작성
튜닝 평가방법 오씨이 디히보
  OLTP 
    TPC-C - 5가지 동시 발생 트랜잭션들의 조합
    TPC-E - TPC-C 인위적 측정점수 향상 개선 
  DSS 의사결정시스템 (DW, OLAP등) Decision Support System
    TPC-H - Ad-hoc query 실행 성능 평가
    BORD - ORD의 벤치마크 테스트

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
