---
title: 도커
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
      I. 컨테이너 기반 오픈소스 가상화 플랫폼, 도커
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 도커의 정의
        </div>
        <div class="para-cntnt">
            리눅스 컨테이너기반으로 APP 격리실행, 이미지, 네트워크 제공 오픈소스 기반 가상화 기술 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 도커
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 도커의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/도커.png" alt="도커">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 도커의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 컨데레네 오모이클
  컨테이너 / LXC - 이미지를 실행한 상태 격리공간 
  데몬 / Service - 도커 컨테이너를 관리하는 프로세스
  레지스트리 / Docker hub, registry - 도커 이미지 저장되어 있는 장소 
  네트워크 / Overlay Net - 컨테이너간 네트워크 터널링 
  오케스트레이션 / Swarm, K8S - 멀티 컨테이너를 조직화
  모니터링 / Prometheus - 컨테이너 모니터링, 로그 확인
  이미지 / aufs, btrfs - 필요한 프로그램 설치후 파일로 만든 것 devicemapper
  클라이언트 / CLI - 데몬과 상호작용하는 Binary 파일
하이퍼바이저와 도커 비교
  추상화 - 전체 H/W Device를 추상화 / OS 커널 
  OS - 여러 OS를 동시 사용 / 단일 OS
  호환성 - 여러 플랫폼 지원 / LXC기반, 리눅스 유리, 타 플랫폼 미비 
  성능 - Guest/Host OS Layer로 인해 저하 / 직접 OS를 Access하여 우수

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
