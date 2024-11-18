---
title: DaaS
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 디지털서비스]
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
      I. 클라우드기반 데스크톱 가상화, DaaS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DaaS의 정의
        </div>
        <div class="para-cntnt">
            가상 데스크톱 제공위해 VDI, Hypervisor, 스트리밍 활용 On demand 클라우드 서비스
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DaaS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DaaS의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DaaS.png" alt="DaaS">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DaaS의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 씬제오프 오프하비
  클라이언트
    Thin Client - 노하드시스템, 클라우드 의존
    Zero Client
  연결중계기
    오토스케일링 - 수요에 따라 스케일아웃, 인
    프로비저닝 - 자원 할당, 시스템 구성
  리소스풀
    OS 풀
    프로파일 풀
  서버
    하이퍼바이저 - 물리적 서버의 리소스를 분리하고 가상 머신(VM)을 생성, 관리
    VDI - 데스크톱 환경을 가상화하여 가상 머신으로 제공
DaaS 와 VDI 비교
  개념 - 클라우드 &lt;&gt; On-Premise
  관리 -  CSP  &lt;&gt; 고객사
  비용납부 - OPEX &lt;&gt; CAPEX
- 공공망분리 규제완화에 따라 논리적 망분리 대안으로 부각

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
