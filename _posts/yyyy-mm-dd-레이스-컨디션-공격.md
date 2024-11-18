---
title: 레이스 컨디션 공격
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
      I. [개념] 공유 자원에 여러 개의 프로세스가 동시에 접근하기 위한 경쟁 상태에서 생성된 임시 파일을 통해 관리자 권한을 탈취하는 공격 기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 레이스 컨디션 공격의 정의
        </div>
        <div class="para-cntnt">
          프로그램 실행 전(임시파일 생성 자제, umask를 취하 022로 유지)
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 레이스 컨디션 공격
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 레이스 컨디션 공격의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/레이스-컨디션-공격.png" alt="레이스 컨디션 공격">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 레이스 컨디션 공격의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          프로그램 실행 중(임시파일에 링크 존재 여부 검사, 임시파일 생성 시 랜덤이름사용)

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
