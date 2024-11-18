---
title: TPM
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 컴퓨터구조]
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
      I. 시스템의 무결성 보장, TPM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. TPM의 정의
        </div>
        <div class="para-cntnt">
            시큐어부팅과 시스템무결성 제공위해 암호화, 무결성점검, 레포트 제공 하드웨어 보안모듈
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. TPM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. TPM의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/TPM.png" alt="TPM">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. TPM의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          표준 
  ISO/IEC 11889
구성요소 스메리 디인펌
  기능
    RTS - RSA 알고리즘 사용 스토리지 암복호화 수행 (Root of Trust for Storage)
    RTM - 부팅시 변경 조작 점검과 무결성 증명 (Root of Trust for Measurement)
    RTR - 무결성인증 요청시 RTM 정보제공 역할 (Root of Trust for Report)
  종류
    Discrete TPM - 별도 IC칩으로 추가 장착하는 형식
    Integrated TPM - 칩셋에 통합되어 기능이 제공
    Firmware TPM - 메인보드 UEFI 펌웨어에서 지원
TPM HSM 비교 (Hardware Security Module)
  형태 - 시스템 구성요소 &lt;&gt; 독립장비
  사용 - PC &lt;&gt; 금융
  인증수준 - 없음 &lt;&gt; FIPS 140-2 
- TPM 2.0은 AES 와 SHA 256 알고리즘 지원

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
