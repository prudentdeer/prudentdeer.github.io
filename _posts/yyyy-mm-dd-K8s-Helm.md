---
title: K8s Helm
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
      I. 쿠버네티스 패키지 통합관리, Helm = NPM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. K8s Helm의 정의
        </div>
        <div class="para-cntnt">
            쿠버네티스 환경 안에서 필요한 패키지를 검색, 공유, 설치 및 관리를 하기 위한 패키지 매니저
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. K8s Helm
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. K8s Helm의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/K8s-Helm.png" alt="K8s Helm">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. K8s Helm의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  기본구성 
    Helm Client - 서버를 대상으로 명령을 지시
    Helm Tiller server - 전달받은 명령을 수행
  Helm 구성
    Chart - 모든 리소스에 대한 정의 포함 yaml 
    Repository - Chart 저장 검색 및 공유 가능공간
    Release - Chart가 클러스터 내 배포될 때마다 새로운 Release 생성
명령어
  helm create - 초기 helm Chart를 생성하는 명령어
  helm search repo - Repository에서 기 구성된 Chart를 조회
  helm install - 클러스터에 Chart 또는 Release를 이용하여 패키지 설치
  helm uninstall - 클러스터에 기 설치된 패키지를 삭제
- Node.js의 npm Python의 pip 과 동일한 개념

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
