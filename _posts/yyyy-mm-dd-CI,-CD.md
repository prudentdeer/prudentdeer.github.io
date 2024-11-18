---
title: CI, CD
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
      I. DevOps 방법론, CI, CD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CI, CD의 정의
        </div>
        <div class="para-cntnt">
            SW 개발시 소스코드를 지속적 통합하고 자동화를 통해 짧은 주기로 배포하는 데브옵스의 방법론
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. CI, CD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CI, CD의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/CI,-CD.png" alt="CI, CD">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. CI, CD의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          필요성
  에러의 조기 발견 / 배포 용이성 확보 / 자동화 
기술요소 버통빌자
  버전관리 / GIT, SVN - 파일 저장, 변경사항 기록
  통합서버 / Hudson, Jenkins - 작업을 통합적 자동화
  빌드스크립트 / 스크립트, 배치파일 - 자동화구현 쉘 스크립트
  자동화 테스트 / SonarQube - 결과를 확인하는 테스트
CI/CD 와 데브옵스의 비교
  개념 - 지속 통합 배포 &lt;&gt; 개발 운영 병행
  목표 - 구축과 배포의 자동화 &lt;&gt; 협업을 통한 간소화
  특징 - 데브옵스의 방법론 &lt;&gt; 애자일 기반의 민첩한 개발

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
