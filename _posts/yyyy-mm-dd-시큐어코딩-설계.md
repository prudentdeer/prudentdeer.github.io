---
title: 시큐어코딩 설계
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 필수암기]
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
      I. 보안취약점을 최소화하기 위한 시큐어코딩
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 시큐어코딩 설계의 정의
        </div>
        <div class="para-cntnt">
            안정성과 신뢰성확보를 위해 소스코드 개발 진행 전 설계 산출물을 기반으로 확인하는 설계방법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 시큐어코딩 설계
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 시큐어코딩 설계의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/시큐어코딩-설계.png" alt="시큐어코딩 설계">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 시큐어코딩 설계의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          적용대상
  행정기관 및 공공기관 정보시스템 감리대상 정보화사업
적용범위 입보에세
  입력데이터 검증 및 표현 - 입력에 의해 발생하는 취약점을 제거
  보안기능 - 접근 제어, 권한 관리, 비밀번호 설계 취약점 제거
  에러처리 - 에러 및 오류 상황의 불충분한 사전 정의로 데이터 유출
  세션통제 - 세션 간 데이터 공유 / 미허가 사용자 접근 / 만료 시간 미산정 약점 제거

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
