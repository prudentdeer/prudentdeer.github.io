---
title: 행위기반 탐지
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
      I. 엔드포인트 보호를 위한, 행위기반 탐지기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 행위기반 탐지의 정의
        </div>
        <div class="para-cntnt">
            악성코드 실행파일의 실행을 통해 이전까지 알려지지 않은 악성 코드를 탐지하는 방법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 행위기반 탐지
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 행위기반 탐지의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/행위기반-탐지.png" alt="행위기반 탐지">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 행위기반 탐지의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          대응전략
  파일확보
    의심파일 필터링 - 미확인 프로그램의 우선 차단
    시나리오 작성 - 알려진 시그니처 기반 악의적 코드 수행 시나리오 작성
  분석
    Rootkit 실행 - 악성코드 은닉을 위한 행위 탐지
    Shell Code Exploit - DLL 실행 후 의도되지 않은 코드의 실행 확인
    외부파일 다운로드 - 파일 행위 중 외부로부터의 파일 다운로드 시도 감지
    EPO 공격 탐지 - Entry Point Obscure 탐지, 코드 중간 악성코드 삽입 행위 탐지
  사후대응
    악성코드 판단 - 분석결과 기존 시그니처 기반 이상 행동이 탐지되면 차단

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
