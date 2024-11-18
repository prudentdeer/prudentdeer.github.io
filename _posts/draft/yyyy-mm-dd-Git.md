---
title: Git
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
      I. 체계적인 Code 관리체계, GIT
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Git의 정의
        </div>
        <div class="para-cntnt">
            로컬에서 자신의 개발소스 관리하고 원격 저장소에 백업과 협업 가능 지원하는 형상관리 도구
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Git
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Git의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Git.png" alt="Git">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Git의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  저장소
    Working Directory - 작업을 하고 있는 프로젝트 디렉토리
    Local Repo - commit 된 파일 저장소
    Remote Repo - push 된 파일 저장소
  명령어
    Commit - 변경된 파일 차이를 로컬 저장소에 기록함 
    Push  - 최종 버전을 원격 저장소에 보냄 
    Fetch - 원격 저장소의 소스를 로컬 저장소로 가져옴
    Pull - 타인의 최종 버전을 로컬 버전과 동기화(Merge) 시킴 
브랜치 전략 깃헙랩 5 2 3
  Git Flow / 5개 - Master / Develop / Release / Feature / Hotfix
  Github Flow / 2개이상 - Master / Feature Branch
  Gitlab Flow / 3개이상 - Master / Production / Pre-Production / New branch

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
