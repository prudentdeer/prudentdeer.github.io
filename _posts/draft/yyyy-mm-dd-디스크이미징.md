---
title: 디스크이미징
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
      I. 사이버 범죄의 증거 수집을 위한, 디스크 이미징
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 디스크이미징의 정의
        </div>
        <div class="para-cntnt">
            디스크의 원본 훼손을 방지, 저장매체의 물리적 섹터의 비트스트림 사본 생성하는 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 디스크이미징
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 디스크이미징의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/디스크이미징.png" alt="디스크이미징">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 디스크이미징의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          용도 (응용활용 / 시스템활용) 포가백복
  포렌식 분석 - 증거수집, 무결성유지
  가상화 - 오토스케일링, 가상시스템 배포
  백업 - OS 백업, 데이터 백업
  시스템복구 - OS 복원, 장애 복구
유형
  Disk To Disk - 원본 저장매체의 모든 내용을 물리적 으로 복사하여 사본을 만드는 방식
    - 하드웨어 전용장비 사용, 컴퓨터 연결 없이 가능, 단순 비트스트림 복제, 속도가 빠름
  Disk To File - 원본 저장매체의  모든 내용을 압축하여 이미지 파일로 생성하는 방식
    - 쓰기방지장치 사용, 전용 소프트 웨어 사용, 파일형태의 이미지, 분석가 배포 용이
절차 연증쓰실
  연계보관성 확인 - 올바르게 문서화 되었는지 확인
  증거 봉인상태 촬영 - 봉인상태로 무결성 보존 확인
  쓰기방지 방법 강구 - HW, SW를 이용한 쓰기방지 처리
  이미징 실시 - 이미징 툴을 활용한 이미징 작업 실시
구성요소 논물비실무포
  대상형태
    논리 드라이브 - 논리적으로 파티셔닝 된 볼륨 (C:\, D:\ 등)
    물리 드라이브 - 디스크 전체, MBR 정보와 논리적으로 파티셔닝된 볼륨까지 포함
  전원유무
    비활성 이미징 - 전원이 꺼져있는 기기에서 데이터 수집
    실시간 이미징 - 전원이 켜져있는 기기에서 데이터 수집
  결과물형식
    무가공 파일 - 데이터가 변환되지 않고 그대로 저장
    포렌식 파일 - 데이터가 형식적인 포맷으로 변경
디스크이미징과 파일카빙 비교
  개념 - 데이터 복제 및 보존 &lt;&gt; 손상된 파일의 복구
  목적 - 디지털포렌식, 복구 &lt;&gt; 특정 파일 데이터 복구
  작업단위 - 디스크 &lt;&gt; 파일, 파일조각
  저장형식 - 이미지 파일 &lt;&gt; 개별파일, 조각
  작업방식 - 비트수준 복제 &lt;&gt; 시그니처 분석 

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
