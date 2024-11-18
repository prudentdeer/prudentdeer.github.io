---
title: 파일리스 악성코드
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
      I. 파일설치 없는 해킹, 파일리스 악성코드
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 파일리스 악성코드의 정의
        </div>
        <div class="para-cntnt">
            파일의 설치나 실행없이 악성사이트 통해 프로세스 메모리 상 악성코드 실행하는 해킹기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 파일리스 악성코드
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 파일리스 악성코드의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/파일리스-악성코드.png" alt="파일리스 악성코드">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 파일리스 악성코드의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          
  프로세스 인젝션
  LoL 기법 - 새로운 악성코드, 파일 등이 아닌 원래의 것을 활용, Living Off the Land
  스크립팅

공격절차
  공격자 메일발송 - 악성 사이트 링크포함 스팸메시지
  사용자접근 - 사용자의 링크 클릭
  취약점 익스플로잇 - 취약점 파일 로딩
  메모리 내 주입 - 메모리 상에서 명령어 라인통해 지시사항 실행
  추가실행 - C&amp;C 서버에서 스크립트 다운로드 실행
  자료유출 - 데이터 위치 알아내 해커 전송
대응방안
  관리적
    보안의식 강화 - 진입점인 피해자교육
    다계층 보안 - 사전예방식 network ~ host 보안
  기술적
    SIEM, SOAR, ZTA, CTEM

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
