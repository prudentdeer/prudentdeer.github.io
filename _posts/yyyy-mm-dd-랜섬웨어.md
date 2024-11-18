---
title: 랜섬웨어
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
      I. 인질과 협박, 랜섬웨어
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 랜섬웨어의 정의
        </div>
        <div class="para-cntnt">
            사용자데이터 암호화 후 복호화 키 대가로 협박해 비트코인, 금전을 요구하는 악성코드
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 랜섬웨어
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 랜섬웨어의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/랜섬웨어.png" alt="랜섬웨어">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 랜섬웨어의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          공격절차
  감염
    웹페이지접속 - 랜섬웨어가 유포중인 홈페이지 방문
    랜섬웨어감염 - 이메일, 첨부파일, 링크, APT 등 의해 감염
  암호화
    암호대상검색 - 감염대상 파일 검색
    파일암호화 - 검색된 파일의 암호화 수행
  금전요구
    랜섬노트 - 복호화 키 대가로 비트코인 요구
    다크웹 - 다크웹에 사용자 데이터 판매
대응방안 에공네복
  사전대응
    에어갭백업 - 격리된 공간에 백업
    공격표면감소 - 운영체제 웹브라우저, 브라우저 플러그인 및 소프트웨어 취약점 패치
  사후대응
    네트워크차단 - 망내 전파 가능성
    복구수행 - 파일복구 수행

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
