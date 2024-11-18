---
title: 연결함정
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
      I. 관계성 집합의 의미 불분명 현상, 연결함정
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 연결함정의 정의
        </div>
        <div class="para-cntnt">
            정규화 실패로 관계성이 모호하거나 미존재로 인해 오류 유발하는 ER모델의 관계성 분실현상
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 연결함정
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 연결함정의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/연결함정.png" alt="연결함정">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 연결함정의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          종류 부모균미 단교학 교학생
  부채꼴 함정 / 관계 모호 - 관계가 정의되어 있기는 하지만 관계가 모호 (Fan Trap)
    - 교수가 어떤 단과대학에 재직하는지 알 수 있으나, 어떤 학과에 재직하는지 알 수 없음
  균열 함정 / 관계성 미존재 - 관계가 정의되어 있지만 일부 엔티티간의 관계 누락 (Chasm Trap)
    - 학생이 지도교수를 할당 받지 못한 경우 어느 학과에 속하는지 확인 불가(복학생)
예방방법 정데매프
  정규화 검증 - 설계서 기반 Testcase 통한 데이터 무결성 검증
  데이터모델링 - 설계단계 DB Inspection 실시
  CRUD 매트릭스 - 프로세스기반 Entity 관계 Cross Check, 설계단계 조기 미정규화 발견
  프로토타입

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
