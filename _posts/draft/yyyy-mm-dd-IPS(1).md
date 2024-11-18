---
title: IPS
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
      I. 침입탐지와 실시간 방어를 위한 솔루션, IPS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IPS의 정의
        </div>
        <div class="para-cntnt">
            IDS의 오탐지, 미탐지의 문제 해결위해 침입탐지와 동시에 실시간으로 방어가 가능한 보안 솔루션
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IPS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IPS의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IPS.png" alt="IPS">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IPS의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          요건
  정확성, 관리정책, 확장성과 처리속도, 철저한 사후조사, 멧갈프 법칙의 정의
유형 힙스닙스
  HIPS (Host Based IPS)
    개념 : 특정 서버 기반으로 어플리케이션 소프트웨어 형태로 설치, 시큐어 OS와 유사기능 수행
    특징 : 서버 기반의 커널 조작 등 불법적인 서버 침입 방지
    목적 : 시스템 불법 침입 및 바이러스, 해킹 등 호스트 기반 보호
    장점 : 커널 상에서 불법 응용 실행 방지 업데이트 및 패치 관리 용이
    단점 : 에이전트 설치비용 증가, 정상적인 응용 프로그램 방해 가능성 발생
  NIPS (Network Based IPS)
    개념 : 방화벽처럼 네트워크 인라인 모드로 설치되어 공격을 차단해주는 기능 수행, 정책에 근거한 패턴 탐지
    특징 : DDoS, 버퍼 오버 플로우 등 네트워크 기반 공격에 빠른 대응과 사전 차단 및 방비
    목적 : 네트워크 기반의 공격 등 과도한 트래픽 공격 방지
    장점 : 하드웨어 기반의 빠른 대응속도, 대부분 자동 수행 기능
    단점 : 네트워크 상의 단일 실패 점 존재로 여분의 장비 필요, 보안 업데이트에 의존

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
