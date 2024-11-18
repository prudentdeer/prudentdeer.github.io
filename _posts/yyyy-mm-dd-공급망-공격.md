---
title: 공급망 공격
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 경영전략]
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
      I. 공급망 공격
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 공급망 공격의 정의
        </div>
        <div class="para-cntnt">
            SW 개발, 배포, 공급과정에서 취약한 서버, PC등에 침투해 악성코드를 유포하는 공격기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 공급망 공격
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 공급망 공격의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/공급망-공격.png" alt="공급망 공격">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 공급망 공격의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          공격절차 개변내범외
  개발환경 침투 / 서버, 인증서, 취약점 - 원격근무자의 권한 이용 개발 환경 침투
  변조 업데이트 유포 / 업데이트 파일 - 업데이트 모듈 위장, 파일의 변조 파일을 유포
  내부확대 / 다수 고객사 - 개인 사용자 PC 및 기업 내부 서버 /PC 감염
  범위확대 / 내부 타 서버 - 설정 타겟 또는 내부 기밀 서버 또는 관리자 서버 침투
  외부확대 / 외부 PC, 서버 - 공급망 연계 회사나 고객사 관리 PC 및 서버
대응방안 인시업대소
  인증서관리 - 별도 인증서 관리 시스템 구축, 인증서 사용 로그 기록 및 승인
  시스템관리 - 시스템 망 분리, 시스템 접근통제
  업데이트 체계 - 업데이트 서버 IP, URL 변조 확인, 원격 업데이트 포트 관리
  대응체계 - 인증서 폐기 절차 수립, 침해사고 신고 및 기술지원 요청
  SBOM
공격유형 하부위인 씨원스워
  HW측면
    하드웨어 트로이 (HT) - 마이크로칩 등이 포함된 회로 이용한 공격기법
    부채널공격 (SCA) - 암호모듈이 포함된 전자장비에서 암호 알고리즘이 수행되는 시점 공격
    FPGA공격 - 회로 제작 후 회로수정이 가능한 FPGA의 특성을 이용하여 공격
  SW측면
    위변조 패치배포 - 업데이트 서버의 파일 및 명령어 배포 기능을 이용 공격기법
    인증서 탈취 - 탈취한 인증서로 악성프로그램 인증을 통해 무결성 검증 우회 및 추가공격에 활용
    CI/CD 취약점 - 원격코드실행 및 관리자 포탈 접근 취약점 등을 통한 개발 및 운영망 공격
    원격접속 프로토콜 - Telnet, SSH, FTP, RDP, VPN 등 접근계정 악용
    관리자페이지 노출 - 개발망, 운영망 등에서 관리기능을 제공하는 페이지의 취약점 및 계정정보 유출
  인적측면
    스피어 피싱 - 주요시스템에 접근가능 사용자에게 이메일, 홈페이지 매체이용 악성코드 유포
    워터링 홀 - 공격대상 접근 후 Lateral Movement, Privilege Escalation
대응방안 위필씨니 보전
  HW측면
    위조부품 보안강화 - 하드웨어 보안검증 정책, 표준, 프로세스 정립
    FPGA 보안강화 - 위협모델링을 통한 위협요인 도출, field programmable gate array
  SW측면
    C-SCRM 수립 - 소프트웨어 개발보안 요구사항 정의
    NIST SP 800 - 
  인적측면
    보안인식 제고 - 공급업체의 공급망 보안교육 수행
    전담기관 운영 - 하드웨어 및 소프트웨어 보안강화를 위한 전담기관
-  SW 유지관리 활동 전반에 SBOM을 연계하여 취약점에 대한 지속적인 모니터링

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
