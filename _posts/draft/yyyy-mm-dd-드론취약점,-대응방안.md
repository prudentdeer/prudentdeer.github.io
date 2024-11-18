---
title: 드론취약점, 대응방안
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 디지털서비스]
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
      I. 드론의 취약점 스재 퍼키도익하중 하평
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 드론취약점, 대응방안의 정의
        </div>
        <div class="para-cntnt">
              GPS Spoofing - 위조 GPS 신호를 통한 기체납치
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 드론취약점, 대응방안
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 드론취약점, 대응방안의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/드론취약점,-대응방안.png" alt="드론취약점, 대응방안">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 드론취약점, 대응방안의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
              GPS Jamming - 방해전파를 통한 성능저하, 추락사고 유발
  네트워크
    Fuzzing - 데이터 무작위 주입을 통한 기체의 오작동 유도
    Key Logger - 기체에 입력된 모든 정보 탈취, 유출가능
    DoS - 과도한 패킷 주입을 통한 시스템 과부하 발생
    Exploit - 원격 코드실행 취약점 이용하여 공격자가 조종
    Hijacking - 키로거가 설치되어 무인 항공기 조종권 탈취
    MITM - 위장을 통한 사용자 개인정보 데이터 탈취
  애플리케이션
    하드코딩 - 주요 데이터 어플리케이션 내 직접 배치
    평문노출 - 암호화되지 않은 데이터 노출로 인한 개인정보 탈취
취약점 대응방안 브마 전신 난원화
  관리적 
    VPN - VPN 기술을 활용한 영상정보의 기밀성 확보
    Masking - 마스킹 기법을 활용한 영상정보의 암호화
  물리적
    전용센서 - 스푸핑 탐지와 위치 복원을 위한 장치 내장
    GPS 신호인증 - GPS 신호인증을 통한 스푸핑 공격신호 탐지
  기술적
    난수생성기 - 난수를 이용하여 암호키 생성하고 보호
    One-time Pad - 관제소와 데이터 전송시 기밀성과 무결성 확보
    화이트박스 암호 - 데이터와 암호화 키 보호, 사용자 인증
- 드론에 취약점이 하나도 없더라도 통하는 전자기오류주입, EMFI 대응필요
- ElectroMagnetic Fault Injection
- 드론 내 펌웨어가 업데이트 되는 때에 전자기와 관련된 오류를 유발시킬 수 있고
이 오류를 순간적으로 익스플로잇 함으로써 공격자가 장비 내 주 프로세스를 통해 
코드를 실행시킬 수 있게 되며, 이로써 장비를 완전히 장악할 수 있게 된다는 것 

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
