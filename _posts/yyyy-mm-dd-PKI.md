---
title: PKI
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
      I. 공개키 기반의 인프라 구조, PKI
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. PKI의 정의
        </div>
        <div class="para-cntnt">
            인증기관에서 공개키와 개인키 포함 인증서 발급받아, 안전 비밀통신 가능케 하는 기반 인프라 구조
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. PKI
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. PKI의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/PKI.png" alt="PKI">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. PKI의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 인등원디 코스
  인증기관 (CA) - 인증서의 등록, 발급, 조회 등 관리 / CRL(Certificate Revocation List) 생성
  등록대행기관 (RA) - 인증서 등록 및 사용자 신원확인을 대행
  원격등록기관 (LRA) - 가입자 신원확인 및 인증서 발급정보 등록
  디렉터리 - 인증서 및 CRL을 저장하고 사용자에게 서비스하는 역할
  Certificate Repository - 인증서 및 인증서 폐기 목록(CRL)을 보관
  X.509 - CA에서 발행하는 인증서를 기반으로 한 공개키 인증서 표준 포맷
검증방식
  CRL - 인증서에 대한 폐지 목록
  OCSP - 실시간 인증서 유효성 검증 (Online Certificate Status Protocol)
  SCVP - 인증서 체인제공 (Simple Certificate Validation Protocol)

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
