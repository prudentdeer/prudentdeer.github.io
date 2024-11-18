---
title: HSM
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
      I. HSM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. HSM의 정의
        </div>
        <div class="para-cntnt">
            인프라 및 프로세스를 보호하기 위해 암호키 물리적으로 저장, 관리하는 하드웨어 보안 모듈
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. HSM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. HSM의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/HSM.png" alt="HSM">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. HSM의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          기술요소 메난유설 피네유클
  메시지 기밀성 / 무결성
    블록 암호 – ARIA, SEED, LEA, HIGHT, 기밀성(ECB, CBC, CFB, OFB, CTR), 기밀성/인증(CCM, GCM)
    해시 함수 – SHA-2/3, LSH, SHA-224/256/384/512, LSH-224/256/512
    메시지 인증 – 해시함수 기반 HMAC, 블록암호 기반 CMAC, GMAC
    난수발생기 – 해시함수 기반 Hash_DRBG, HMAC_DRBG, 블록암호 기반 CTR_DRBG
  암호키 관리
    공개키 암호 – RSAES, 공개키 길이: 2048, 3072, 해시함수: SHA-224, SHA-256
    전자서명 – RSA-PSS, KCDSA, EC-KCDSA, ECDSA, 공개키 길이: 2048, 3072, 해시함수: SHA-224, SHA-256
    키 설정 – DH, ECDH, 공개키 길이: 2048, 개인키 길이: 224, 256
    키 유도 – KBKDF, PBKDF, HMAC, CMAC, HMAC
유형
  하드웨어 내장형
    PCI 기반 HSM – 서버 혹은 보안 시스템 내 PCI 타입으로 장착
    네트워크 HSM – HSM 전용 Appliance 장비로 고성능 필요 시 사용
  이동식
    USB기반 HSM – 휴대형 USB 형태로 일반적으로 보안 토큰으로 통칭
    Cloud HSM – Cloud 서비스에서 관리형 HSM 서비스로 사용
TPM HSM 비교 (Hardware Security Module)
  형태 - 시스템 구성요소 &lt;&gt; 독립장비
  사용 - PC &lt;&gt; 금융
  인증수준 - 없음 &lt;&gt; FIPS 140-2 

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
