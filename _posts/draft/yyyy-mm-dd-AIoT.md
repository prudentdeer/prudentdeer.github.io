---
title: AIoT
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 네트워크]
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
      I. 지능형 사물인터넷, AIoT
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. AIoT의 정의
        </div>
        <div class="para-cntnt">
            기존 IoT 에 인공지능 기술 적용하여 실시간 분석, 자동화 결정 제공하는 융합기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. AIoT
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. AIoT의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/AIoT.png" alt="AIoT">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. AIoT의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          등장배경
  기존 IoT 한계
    빅데이터 처리, 디바이스 증가
  인공지능 발전
    온디바이스AI, LLM
보안취약점 적백개센 암펌네접
  AI 측면
    모델측면
      적대적공격 - 잘못된 결과값을 유도
      백도어학습 - 특정 패턴에 반응하는 백도어
    데이터측면
      센싱데이터추론 - 센서 데이터를 이용해 사용자의 현재 상황 추론
      개인정보 추론 - 데이터를 이용해 민감한 정보를 추론
  IoT 측면
    IoT 데이터 
      데이터 암호화 부재 : IoT 송수신 구간 등 비 암호화 및 프라이버시 보호부재
      비신뢰 펌웨어 : 펌웨어 패치 시 서버 혹은 전송장비의 인증로직 없음
    IoT 통신 
      불안정한 네트워크 : 불필요 노출포트, 원격제어 허용, 권한상승 허용
      접근통제 부재 : IoT기기로의 진입, 진출 구간의 전송통제 기능 누락
- IoT 보안위협 상속과 더해 AI 취약점 배가
보안 티스 타이 멀메
  HW - 별도의 하드웨어 모듈 추가
    TPM - 암호키, 패스워드, 인증서 저장 보안모듈 (Trusted Platform module)
    SE - 암호화데이터 저장 및 변조방지 적용 칩 (Secure Element)
  SW 플랫폼 - AP 칩 이용해 구현
    TEE - 내부 코드와 데이터 보호위한 격리 실행환경 (Trusted Execution Environment)
    ARM Trust Zone - 프로세서안에 독립적인 보안구역
    Intel SGX - 신뢰가능 실행환경 구현 명령코드세트
  RISC-V (리스크 파이브) - RISC 기반 축소명령어집합 
    RISC-V Multizone - 모든 도메인을 격리하는 제로 트러스트 모델을 사용
    RISC-V 메모리격리기술
    RISC-V 하드웨어기반 메모리 무결성 기술

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
