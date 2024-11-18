---
title: 쿠버네티스
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
      I. Container-Driven 오케스트레이션, K8S
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 쿠버네티스의 정의
        </div>
        <div class="para-cntnt">
            다수의 컨테이너의 배포, 확장 및 관리 자동화를 위한 오픈소스 기반 오케스트레이션 플랫폼  
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 쿠버네티스
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 쿠버네티스의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/쿠버네티스.png" alt="쿠버네티스">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 쿠버네티스의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 마매에이스 워큐큐도팟
  마스터 노드   
    컨트롤 매니저 - 전체 시스템을 관리하고 통제하는 에이전트 
    API 서버 - 각 노드의 Kubelet과 통신하기 위한 API 서버 
    Etcd - 설정 파일들을 저장하고 있는 저장공간 
    스케줄러 - 적재적소에 맞는 노드에 Pod를 할당해주기 위한 JOB스케줄러 
  워커 노드   
    Kubelet - 마스터 명령을 받아서 수행하고, 노드의 상태 마스터로 전달 
    Kube-proxy - 네트워크 트래픽 컨테이너로 라우팅, 로드밸런싱 
    Docker - 컨테이너를 실행하는 컨테이너 런타임
    Pod - 쿠버네티스의 작업단위
쿠버네티스를 활용한 배포방법 롤블카
  롤링 배포 / 순차배포 - 순차적으로 새 버전의 POD으로 교체
  블루(구) - 그린(신) 배포 / 일괄배포 - Downtime을 최소화, 한번에 모든 트래픽 이동
  카나리 배포 / 테스트배포 - 사용자에게 테스트를 실시하여 검토후 교체 (가스누출 광부들)

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
