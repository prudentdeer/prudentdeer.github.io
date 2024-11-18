---
title: Web Shell
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
      I. Web Shell
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Web Shell의 정의
        </div>
        <div class="para-cntnt">
            파일 업로드 취약점 이용해 원격에서 대상 웹서버에 명령할 수 있도록 작성된 웹 스크립트 파일
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Web Shell
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Web Shell의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Web-Shell.png" alt="Web Shell">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Web Shell의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          (asp, jsp, php, cgi)  
- 웹 서버에 명령을 실행하여 관리자 권한을 획득해 행하는 공격 방법 
관리자 권한을 획득 ,  파일업로드 취약점이용, 다양한 공격 가능
유형 원올인멀
  단독파일
    Oneline 웹쉘 
    All-in-one 웹쉘
    Injection 웹쉘 - 기존 존재 소스코드에 웹쉘구문 삽입
  기타
    Multi Division 웹쉘 - 공격자가 전송하는 다중분할 파라미터 재조합

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
