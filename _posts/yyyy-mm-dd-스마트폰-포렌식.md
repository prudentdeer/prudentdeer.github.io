---
title: 스마트폰 포렌식
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
      I. &lt;법적 증거자료 확보 위한, 스마트폰 포렌식의 개요&gt;
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 스마트폰 포렌식의 정의
        </div>
        <div class="para-cntnt">
            스마트폰 내의 정보에 대하여 법정에서 증거로서의 증거 능력을 갖게 하기 위한 법률적/수사적/기술적 분석과정
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 스마트폰 포렌식
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 스마트폰 포렌식의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/스마트폰-포렌식.png" alt="스마트폰 포렌식">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 스마트폰 포렌식의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          절차
  1 현장보존 : 스마트폰 발견 현장에서 사진을 찍어 현장 보존, 스마트폰이 켜져 있는 경우 화면 사진 캡쳐 / 증거훼손방지, 촬영, 캡쳐
  2 증거확보 : 스마트폰 상태 변경 방지를 위해 네트워크 차단, 전원공급 통해 활성 데이터 보존 / 네트워크 차단, 전원공급
  3 데이터 추출 및 분석 : 법적 효력을 위한 수사 범위, 권한 등 검토, 데이터 추출 및 분석 / 법적 효력 검토, 추출, 분석
  4 보고서 작성 : 사건정보, 증거 획득 과정, 분석 결과 등 작성 / 증거 및 분석 객관성 확보
데이터 추출/분석 방법
  포렌식 데이터 추출
    논리적 데이터 추출
      - USB 인터페이스를 통해 저장된 파일과 디렉토리 추출
      - 안드로이드 : 슈퍼유저 권한 획득(루팅), 데이터 추출
      - IOS : 슈퍼유저 권한 획득(탈옥), 데이터 추출
    물리적 데이터 추출
      - 플래시 메모리 전체를 비트 단위로 복사
      - 운영체제 명령어 사용, JTAG 포트 이용, 메모리칩 직접 분리
  포렌식 데이터 분석
    File Signature 분석 : 파일 내용 중 특정 값으로 파일 유형 판단
    File Hash 분석 : 해시 값을 이용하여 파일의 변경 여부 등을 확인
    TimeLine 분석 : 생성/수정/접근 시간을 의미하는 MAC Time 분석을 통해 사용자의 기기 사용 여부 추적
    Window Registry 분석 : 시스템 설정 정보, 사용자 정보, 응용 프로그램 정보 등을 통해 최근 사용한 파일 또는 프로그램 추적
증거 추출 도구
  QPST : 퀄컴, 내장메모리, FS, 데이터 추출, 삽입/쓰기방지 없음/불안정
  EasyCDMA : Pinksoft사 PC연결 툴, FS, 데이터 추출 삽입/쓰기방지 없음/불안정
  Bitpim : GNU사, opensource, FS, 데이터 추출 삽입/쓰기방지 있음/매우 안정

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
