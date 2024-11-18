---
title: MLOps
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
      I. 머신러닝 오퍼레이션 자동화, MLOps
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MLOps의 정의
        </div>
        <div class="para-cntnt">
            머신러닝과 데이터 생명주기 전과정에서 재학습, 재구축, 재배포 자동화 방법론
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MLOps
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MLOps의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MLOps.png" alt="MLOps">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MLOps의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          프로세스 CI CD CT 
  데이터
    드리프트관리
    ETL 수행
  지속적 통합 CI 
    빌드, 테스트
    레파지토리 통합
  지속적 배포 CD
    파이프라인 구축
    자동배포
  지속적 학습 CT
    데이터 업데이트
    모델 재학습
파이프라인 트리거 온스새성분
  온디맨드 - Ad-hoc방식으로 파이프라인이 임시 수동 실행
  스케줄에 따라 - 매일, 매주 또는 매월
  새로운 데이터 - 데이터 업데이트시
  성능저하시 - 성능 저하가 눈에 띄는 경우 모델이 재학습
  분포변화 - Feature들의 데이터 분포에 유의미한 변화

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
