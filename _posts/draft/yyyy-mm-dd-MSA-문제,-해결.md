---
title: MSA 문제, 해결
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
      I. MSA 문제점 및 개선방안
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MSA 문제, 해결의 정의
        </div>
        <div class="para-cntnt">
            기술적 측면 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MSA 문제, 해결
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MSA 문제, 해결의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MSA-문제,-해결.png" alt="MSA 문제, 해결">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MSA 문제, 해결의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
              장애추적 및 모니터링 - 하나의 메뉴가 다양한 서비스로 구성되어 있을 때 어려움
    트랜잭션 제어문제 - 분산 데이터를 하나의 트랜잭션 처리가 불가함 
    성능적 오버헤드 - API 통신을 JSON이나 XML 데이터로 전달하여 Marsharing 오버헤드 발생 
  조직적 측면     
    서비스간 의존성 roll 관리 부족 - 통합테스트 시 조직간 책임 우선순위 문제 발생
    통합테스트시 협업 - 각 조직간 테스트 환경 구축 문제로 복잡도 증가 
    역할 중심의 팀 모델 해체 - 기업내 거버넌스 구조가 변화되어야 하는 피로도 존재
해결방안
  기술적 측면 
    파일분석 시스템 도입 - 로그파일을 수집하고 분석할 수 있는 시스템 구성 
    Composite 서비스 구현 - DB To DB간 서비스 I/F 구현
    클라우드 환경 도입 - 가상화 기술을 이용하여 경량화된 VM 환경 제공 
  조직적 측면 
    roll-out 관리 부서 및 계획 - 각 팀 간의 역할을 정의할 수 있는 부서 마련 
    테스트 플랫폼 및 조직구성 - MSA 전문적인 테스트 팀 구성 및 QA 문서화
    Cross Functional팀 구성 - 기능 및 서비스 단위의 팀 전환에 중점

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
