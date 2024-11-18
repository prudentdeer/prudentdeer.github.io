---
title: 샤딩
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
      I. 분산처리를 위한, Sharding의 개념 DB, 샤드키
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 샤딩의 정의
        </div>
        <div class="para-cntnt">
            DB 성능향상 위해 하나의 DB를 여러개의 DB에 샤드 키 이용 저장하는 분산 DB 관리기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 샤딩
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 샤딩의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/샤딩.png" alt="샤딩">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 샤딩의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          장점
  여러 인스턴스로 분산하여 처리 &gt; 성능과 확장성
분할방법 수범키디
  수직분할 - 테이블 별 서버를 분할 / 프로필 서버, 친구 리스트 서버, 콘텐츠용 서버
  범위분할 - table이 거대해지는 경우 분리 / 지역정보, 연도별, 우편번호를 이용
  키, 해쉬분할 - 해쉬함수 값을 이용 서버를 정함 / 사용자ID가 숫자일 경우 나머지연산을 이용
  디렉토리 - 추상화된 파티셔닝 서비스를 생성 / 샤드키를 look-up, 구현은 DB와 캐쉬를 조합
구성요소
  Shard DB - 분할된 테이블과 데이터를 포함하고 있으며, 실제로 사용자 요청을 처리하는 데이터베이스
  Metadata - shard DB를 선택하기 위한 정보 및 세션을 생성하기 위한 정보를 포함
  shard key - (column)sharding된 테이블에서 shard를 선택하기 위한 식별자로 사용되는 칼럼
  shard key data - 질의 중 shard를 식별하기 위한 힌트에 해당하는 shard key의 값
  shard ID - shard DB를 식별하기 위한 식별자
  proxy - 실제 질의 처리할 shard DB로 요청을 전달 역할을 하는 CUBRID 미들웨어 프로세스

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
