---
title: 데이터 모델링
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
      I. 데이터 표현위한 추상화 방법, 데이터모델링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 모델링의 정의
        </div>
        <div class="para-cntnt">
            현실세계의 업무를 추상화하고 분석과 설계 통해 개념, 논리, 물리관점 데이터 모델 구성작업
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 데이터 모델링
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 모델링의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/데이터-모델링.png" alt="데이터 모델링">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 데이터 모델링의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          모델링 절차 개논물 주후핵관 속엔이 물논반
  개념 모델링
    주제영역 정의 - 데이터 최상위 집합 구분단계
    후보 Entity 선정 - 엔티티 가능성 있는 후보 수집 / 문서, 인터뷰, 경험
    핵심 Entity 정의 - 후보 중 핵심 엔티티 선별 / 본질식별자, 서브타입
    관계 정의 - 엔티티간의 연관성을 정의 / 1:1, 1:M, M:M, 순환
  논리 모델링
    속성정의 - 분해불가 최소 단위로 상세화
    Entity 상세화 - 식별자 확정, 정규화
    이력관리 정의 - 정보로서의 활용성, 추적성 확보
  물리 모델링
    물리환경 조사 - 시스템 구축환경 조사
    논리모델 변환 - 테이블, 속성, 관계, 제약조건 등
    반정규화 - 성능, 개발편의성, 운영단순성 확보
좋은 데이터모델링 요소 재비간통
  설계측면
    재사용성 - 통합 모델이어야만 데이터 재사용성을 향상
    비즈니스 룰 - 업무 규칙을 데이터 모델에 표현하고 이를 해당 데이터 모델을 활용
  유지측면
    간결성 - 데이터를 합리적으로 균형이 있으면서도 단순하게 분류
    통합성 - 공유 데이터에 대한 구조를 여러 업무 영역에서 공동으로 사용

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
