---
title: 데이터 클렌징
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
      I. Garbage in Garbage out, 데이터 클렌징
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 클렌징의 정의
        </div>
        <div class="para-cntnt">
            손상되거나 부정확한 데이터, 이상치 제거 및 식별, 교체, 삭제, 수정하는 프로세스
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 데이터 클렌징
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 클렌징의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/데이터-클렌징.png" alt="데이터 클렌징">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 데이터 클렌징의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          프로세스 대원우유제
  대상정의 - 데이터 클렌징 대상 데이터베이스 범위 정립
  원인파악 - 데이터 결측치 및 이상치 식별
  우선순위 - 클렌징 우선 순위 결정
  유입차단 - 잘못된 데이터 입력되는 원인을 찾아 새로운 규칙 생성
  데이터제거 - 데이터베이스 내부의 결측치 및 이상치 제거
클렌징기법 변파보
  데이터 변환
    코드체계변환 - 다양한 형태의 코드 값을 단일 형태로 변환 (예: 성 별)
    형식 재구성 - 다양한 형식의 데이터 값을 단일 형식으로 전환 (예: 일 자)
    수학적 변환 - 다양한 형식의 단위 값을 단일 단위 값으로 변환 (화폐단위)
  데이터 파싱 - 데이터 정제 규칙을 적용하기 위해 유의미한 최소 단위로 분할하는 작업
  데이터 보강 - 변화, 파싱 등을 통해 추가 정보를 반영하는 작업

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
