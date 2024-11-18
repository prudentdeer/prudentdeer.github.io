---
title: IaC
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
      I. 코드로 인프라를 제어하는, IaC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IaC의 정의
        </div>
        <div class="para-cntnt">
            인프라 구성을 위해 코드이용 인프라 생성, 변경, 프로비저닝하는 자동화 관리기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IaC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IaC의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IaC.png" alt="IaC">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IaC의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          주요기술 명선닥탭
  명령형
    Docker Compose - 도커 컨테이너 설정    
    AWS CloudFormation - 리소스 프로비저닝
    Kubernetes Kubectl - 클러스터 작업관리    
  선언형
    Terraform - CSP 연동, 인프라관리
    Ansible - 다양한 설정을 파일로 관리
    Puppet - agent 방식과 non-agent 방식 제공
명령형, 선언형 비교
  작성 - 명령어와 절차 &lt;&gt; 최종상태
  기반 - 스크립트 &lt;&gt; 설정파일
  변경관리 - 어려움 &lt;&gt; 쉬움
  가독성 - 낮음 &lt;&gt; 높음

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
