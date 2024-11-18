---
title: 포렌식 증거 수집기법
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
      I. 네트워크 증거수집 트헤보라 
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 포렌식 증거 수집기법의 정의
        </div>
        <div class="para-cntnt">
            IP 헤더 분석 - IP 헤더 정보분석 후 발신자 및 발신내용의 분석
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 포렌식 증거 수집기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 포렌식 증거 수집기법의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/포렌식-증거-수집기법.png" alt="포렌식 증거 수집기법">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 포렌식 증거 수집기법의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            보안장비 로그분석 - 통합로그 관리솔루션 등을 통해 방화벽, IDS, IPS 로그분석
  라우터 분석 - 로그인 사용자, TCP 관련 연결정보 등
시스템 증거수집 주저시공 
  주요 프로세스 - 구동중인 프로세스의 휘발성 정보 수집
  저장매체 및 메모리 - 데이터 이미징, 파일시스템 로그분석, 메모리관련 내용 분석
  시스템 OS 로그 - 윈도우 log, 휴지통, 최근파일 등을 활용해 이력확인 및 데이터 복원
  공유폴더 - 공유폴더 목록과 접속한 기록 수집
응용프로그램 증거수집 메이브응
  메신저 - 대화내용 및 송수신 파일 내역
  이메일 - 송수신 내역, 이메일 서버 확인
  브라우저 - 검색 히스토리, 캐쉬, 쿠키 등의 확보
  응용프로그램 - 스마트뱅킹, MTS, HTS 로그확보

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
