---
title: IoT 보안취약점, 대응방안
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
      I. 사물인터넷 보안 위협요인 CPND 로 정리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IoT 보안취약점, 대응방안의 정의
        </div>
        <div class="para-cntnt">
            노출영역 확대 : 네트워크 연결이 증가함에 따라 노출영역이 함께 확대됨
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IoT 보안취약점, 대응방안
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IoT 보안취약점, 대응방안의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IoT-보안취약점,-대응방안.png" alt="IoT 보안취약점, 대응방안">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IoT 보안취약점, 대응방안의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            자원제약 : 다수의 IoT 기기는 저 사양으로 별도의(임베디드 보안 기술 등) 기술이 요구됨
  개방형 플랫폼 : 리눅스, 개방형 플랫폼 소스는 취약점 발견 및 이를 이용한 공격이 용이함
  낮은 보안수준 : 이미 출시된 다수의 상용 IoT 기기의 보안 수준이 매우 낮음
  피해심각성 및 범위 : 헬스 케어, 자율주행, 교통 시스템 해킹 등은 기계적 장치를 넘어 사람의 생명까지 위협
취약점 약인 암펌 네접
  IoT 접속 
    인증체계 부족 : IoT 특성을 고려한 생체인증,다채널 인증체계 부재
    약한강도 비밀번호 : 초기 비밀번호, 숫자,영문만 이용 10자리 이하 설정
  IoT 데이터 
    데이터 암호화 부재 : IoT 송수신 구간 등 비 암호화 및 프라이버시 보호부재
    비신뢰 펌웨어 : 펌웨어 패치 시 서버 혹은 전송장비의 인증로직 없음
  IoT 통신 
    불안정한 네트워크 : 불필요 노출포트, 원격제어 허용, 권한상승 허용
    접근통제 부재 : IoT기기로의 진입, 진출 구간의 전송통제 기능 누락
보안기술 공상펌경 칩버업부
  공개키 핀 : 인증서가 변조되지 않음을 탐지하여 중간자공격 차단 / 공개키정보 체인검증, 키갱신
  상호인증 : 서버와 기기의 상호 인증된 상태로 안전하게 통신 / 보안칩 키저장, 키 개별화
  펌웨어 암호화 : 펌웨어를 암호화, 서명하여 기밀성, 무결성 확보 / AES-128, RSA-2048
  경량암호화 기술 : 성능이 낮은 IOT기기에서 적절한 수준 암복호화 / LEA, HEIGHT, SIMON, SPECK
  칩 보안 : 기기에 보안칩 장착하고 SW 실행하면서 이상 확인 / SE, TEE, PUF
  버퍼오버플로 방지 : 메모리 랜덤할당, 덮어쓰기 탐지 등 / Stack Smashing Protector향 비밀성
  시큐어 업데이트 : 신뢰할수 있는 방법의 보안패치 / 주기적 패치, 암호 알고리즘
  시큐어 부팅 : 부팅 전 검사를 통해 악성코드 탐지, 위변조 방지 / Root of Trust, RSA 서명

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
