---
title: 큐싱
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
      I. QR코드를 이용한 해킹, 큐싱 
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 큐싱의 정의
        </div>
        <div class="para-cntnt">
            QR코드 스캔사용자를 위장사이트 리다이렉트해 개인정보 탈취, 악성코드 설치 공격기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 큐싱
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 큐싱의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/큐싱.png" alt="큐싱">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 큐싱의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          공격절차 배스리악탈
  QR코드 배포 / 피싱 - QR 코드를 생성하고 피해자에게 악성 링크가 포함된 스팸문자 발송
  QR코드 스캔 / 카메라, 영상 - 피해자는 스팸 문자의 내용을 확인 후 QR 코드 스캔
  리다이렉트
  악성코드설치 / 앱 관리자 - 해커가 의도한 사이트에서 출처를 알 수 없는 앱 다운로드 후 설치
  정보탈취 / 원격제어 - 피해자의 디바이스에 있는 정보 등을 유출
대응방안
  관리적
    SMS 발송정보 / 기업 - 대량 SMS 발송 주체의 경우 발송 주체의 정보를 추가 제공
    사용자교육 - 큐싱트랜드, 위험성 교육
  기술적
    MFA 인증 – 스캔후 다중인증 구조로 단계별 공격대응가능
    디바이스 설정 / 앱 설정 - ‘알 수 없는 출처(미인증) 앱 설치’ 기능 설정 및 유지
- 큐싱이용 멀티팩터 인증수단까지 모두 탈취가능

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
