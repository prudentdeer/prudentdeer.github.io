---
title: O-RAN
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 네트워크]
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
      I. 개방형 무선 접속망, Open RAN 의 개요
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. O-RAN의 정의
        </div>
        <div class="para-cntnt">
            벤더 종속성 탈피하기 위해 RAN 구간에 HW 와 SW 분리, 가상화 적용한 개방형 아키텍처
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. O-RAN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. O-RAN의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/O-RAN.png" alt="O-RAN">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. O-RAN의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          효과 벤장비서
  벤더종속성 탈피 - 개방형 아키텍처, 표준화된 인터페이스를 지원 
  장비선택과 조합 - 자유롭게 혼합하여 무선 통신망을 구축
  비용절감 - 다양성 확보로 무선망 구축과 운용에 소요되는 비용 절감
  서비스혁신 - 새로운 솔루션과 서비스를 제공함에 있어 혁신 가속화
구성요소
  장비
    RIC - 자원을 제어하고 최적화
    O-RU - 안테나 제어기능, 안테나의 방향을 움직여 트래픽이 몰리는 곳을 향함 
    O-DU - 분산기지국 장치, 필요한 데이터 필터링, 신호의 처리 순서를 결정
    O-CU - 데이터 무결성 점검, 압축, 중앙 망에 데이터 전송    
  통신구간
    Front Haul - RU-DU 사이 연결링크
    Mid Haul - DU-CU 사이 연결링크
    Back Haul - 기지국과 네트워크 연결
RAN 과 ORAN 비교
RAN 정의
  이동통신 망의 무선 단말과 접속을 이루는 무선영역을 담당하는 무선 접속망
  공급 - Single Vendor &lt;&gt; Multiple Vendors
  플랫폼 - 종속적 &lt;&gt; 비종속적
  모듈성 - 통합구성 &lt;&gt;  RU DU CU 분리
  애플리케이션 - 사전 프로그래밍 &lt;&gt; 조건에 따른 프로그래밍
O-RAN 국내외 동향 오티오테
  해외
    O RAN Alliance 표준화 논의 - 글로벌 네트워크 기업, 3GPP 연계
    TIFG - 시험검증 절차 정의, Test and Integration Focus Group
  국내
    O RAN 전담반 운영 - ETRI, IITP 참여, 국내 NW 장비 제조사
    테스트베드 구축 - NIA 테스트베드 기반 구축계획

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
