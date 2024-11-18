---
title: DataOps
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
      I. 데이터중심 기업을 위한, 데이터옵스
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DataOps의 정의
        </div>
        <div class="para-cntnt">
            적시적소에 적합한 데이터를 제공하여 신속성을 보장하고, 협업을 지원 자동화 방법론
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DataOps
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DataOps의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DataOps.png" alt="DataOps">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DataOps의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          등장배경
  IT부서 의존적, 충분한 권한 부족, 기술환경 부족
단계별활동 샌스프
  샌드박스 / 데이터 탐색 :  정제되지 않은 원시데이터 탐색 / 비즈니스 가치탐구 
  스테이징 / 품질향상 : 1차적 정제 데이터 세트를 통해 초기 모델 개발 / 품질 수준 향상
  프로덕션 / 가치창출 : 분석모델의 프로덕션 단계로 진화 / 비즈니스 가치 창출
주요기술 오이스인환자
  스토리지 / Git, Dockerhub - 인위적인 변경 사항 관리와 거버넌스 및 반복 개발
  이력관리 / MongoDB - 시스템 및 활동 로그 관리
  인증권한 / Auth0, zerotrust - 환경에 대한 접근 제어
  자동배포 / Jenkins, CircleCI - 하나의 환경에서 프로덕션 환경으로 코드/구성을 이동하는 과정
  환경생성 / Container - 모든것을 가지고 작업할 수 있는 환경 생성 코드와 같은 인프라 취급
  오케스트레이션 / Kubernetes - 관련된 모든 도구를 오케스트레이션하고 테스트 및 모니터링
데이터옵스 vs 데브옵스 
  목표 - 데이터제공 최적화 &lt;&gt; SW제공 최적화
  범위 - 수집, 처리, 분석, 공유 &lt;&gt; 개발, 배포, 운영 
  가치 - 신속성, 협업 &lt;&gt; 협업, 자동화
  활동 - 메타데이터 관리 &lt;&gt; CI/CD, 자동화 
  기술 - Apache Hadoop, Apache Spark &lt;&gt; Jenkins, Docker, Kubernetes
- DataOps + DevOps + MLOps &gt; AIOps

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
