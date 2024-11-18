---
title: 제로트러스트보안모델
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 보안]
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
      I. 제로트러스트 보안모델
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 제로트러스트보안모델의 정의
        </div>
        <div class="para-cntnt">
            시스템에 대한 접속요구가 있을 때 네트워크를 이미 침해상태로 간주하고 지속적 검증하는 보안모델
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 제로트러스트보안모델
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 제로트러스트보안모델의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/제로트러스트보안모델.png" alt="제로트러스트보안모델">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 제로트러스트보안모델의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          핵심원칙 원인마소
  원칙 - 선인증 후접속
  인증체계 강화 - 리소스 접근주체에 대한 신뢰도기반 정책
  마이크로 세그멘테이션 - 단독 네트워크 구역에 개별자원 배치, 지속적 검증
  SDP / 소프트웨어정의 경계 - 네트워크 동적구성, 신뢰확보후 채널 형성
매커니즘 제데 결엔관시
  정책결정지점 PDP - 자원 접근 요구가 있을 때 접속을 결정
  정책엔진 PE - 신뢰도 판단하여 접속허가 최종결정
  정책관리자 PA - PEP에 명령하여 정책실행
  정책시행지점 PEP - 정책에 따른 접속을 시행
도입절차 준계구운 
  준비 - 핵심요소 검토, 현재수준 평가 / 기업망 핵심요소 중심 현재보안수준 평가
  계획 - 성숙도 기반, 기존보안 조화 / 성숙도모델 기반 기존 보안체계 조화설계, 예산검토
  구현 - 자원위치, 솔루션 구현 / 주요자원 위치고려 생태계 적합 솔루션 검토
  운영 - 기본철학, 핵심원칙 / 기본철학 중심 핵심원칙 동작 가능하도록 관리
모델 프레임워크 식기네응데 시자거
  5핵심요소
    식별자 - 고유하게 설명할 수 있는 속성
    기기 - 네트워크 연결된 모든 하드웨어
    네트워크 - 유무선, 클라우드 포함 모든 통신
    응용 워크로드 - 기업관리 등 모든 서비스
    데이터 - 기관 최우선 보호자원
  3교차요소
    시각화 및 분석 - 비정상 행위에 대한 탐지 및 가시성 제공으로 방어 기법 제공
    자동화 및 통합 - SOAR 통해 정의된 프로세스 내에서 자동화된 통합 보안 대응
    거버넌스 - 경영진의 관심, 조직적 문화, DMA 기반의 피드백
성숙도 전초고최
  전통수준 / 수동 - 기둥 간/조직 간 사일로화, 경직된 권한 관리, 시스템 가시성 미흡
  초급수준 / 일부 자동화 - 일부 기둥 간 연계, 내부 시스템 가시성 확대
  고급수준 / 자동화 확대 - 중앙 집중 제어 강화, 기둥 간 통합 정책
  최적수준 / 완전 자동화 -  상황에 따른 동적 정책 적용, 상호 운영성 및 가시성 증대
- 과기부에서 제로트러스트 클라우드형, 구축형 2가지 모델 발표

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
