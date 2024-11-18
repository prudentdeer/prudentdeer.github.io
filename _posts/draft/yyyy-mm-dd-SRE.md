---
title: SRE
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 소프트웨어공학]
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
      I. DevOps 최종진화, SRE
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SRE의 정의
        </div>
        <div class="para-cntnt">
            시스템, 서비스가 적절수준의 안정성을 지속적 달성할 수 있도록 모니터링, 변화관리 지원하는 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SRE
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SRE의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SRE.png" alt="SRE">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SRE의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          핵심요소 모리변용문 
  모니터링 / SLI, SLO – 정량적 모니터링 지표 정의, 안정성 목표를 SLO로 정의
  Incident Response / MTTF, MTTR, Playbook – 빠른 복구로 장애 시간 최소화, Playbook 기반 장애 복구 모의훈련
  변경관리 / 카나리 배포, 롤링 업데이트 – 배포와 업데이트, 변경 관리, 점진적 배포, 장애 시 빠른 파악 및 롤백
  용량계획 / Auto Scaling, 수요기반 예측, 성능튜닝 – 자원 활용 효율성 측면 안정성 최대화
  문화 / Error Budget – 허용되는 장애 시간, 데이터 기반 의사결정, 비난 보다 장애 분석
안정성 확보 활동 조장점매지
  조직 SILO 최소화 / 책임공유 – 조직 간 효과적 협업을 위한 포스트모텀 문화
  장애반응 / Error Budget – 장애 발생 후 회고, 가용성에 대한 적절한 관리
  점진적변화 / 분할정복 – MTTR 최소화를 위한 카나리 배포, 롤링 업데이트 적용
  매뉴얼기반 / 자동화 – 수동 작업량 측정 및 조절, Toil 기반 관리
  지표관리 / 정량화 – 시스템 지표 뿐 아니라 작업 시간, 장애 시간 등
데브옵스와 SRE 비교
  목표 – 개발팀 운영팀 협업 &lt;&gt; 안정적 시스템 관리
  관심 – 개발 배포 통합 &lt;&gt; 확장성, 자동화
  책임 – 책임 공유 &lt;&gt; 개발자 중심
  담당자 – 운영팀 &lt;&gt; 개발팀
- DevOps 적절히 중재, 관리하기 위하여 SRE가 등장

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
