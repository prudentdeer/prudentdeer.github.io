---
title: GitOps
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 프로젝트관리]
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
      I. Git 이용 데브옵스 확장, GitOps
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. GitOps의 정의
        </div>
        <div class="para-cntnt">
            클라우드 네이티브 개발/운영 효율화 위해 코드와 인프라 설정을 Git 통해 자동화하는 방법론
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. GitOps
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. GitOps의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/GitOps.png" alt="GitOps">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. GitOps의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  운영측면 
    Git 레포지토리 - 인프라 및 애플리케이션의 구성을 저장하는 중앙 집중식 저장소
    선언적 인프라 - 시스템의 원하는 상태를 코드 형식으로 선언하는 방식
  프로세스측면
    CI/CD - 코드 Push 시, 파이프라인이 자동 테스트, 빌드, 배포 과정을 실행 
    IaC - Terraform, Ansible, CloudFormation 자동으로 배포 및 관리하는 데 사용 
    모니터링 및 알림 - 상태와 성능을 모니터링하고, 개발자에게 알림을 보내는 도구
깃옵스의 원칙
    선언적 - 모든 시스템은 선언적 설명
    버전과 불변성 - 시스템 상태는 Git 저장, 롤백가능
    자동적용 - 승인 변경사항은 자동 시스템 적용
    지속적 관리 - 배포실패시 경고알림

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
