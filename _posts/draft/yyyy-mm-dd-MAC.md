---
title: MAC
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
      I. MAC (Message Authentication Code)
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MAC의 정의
        </div>
        <div class="para-cntnt">
            비밀키를 사용하여 메시지 무결성과 사용자 인증을 제공하는 해시 알고리즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MAC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MAC의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MAC.png" alt="MAC">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MAC의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 농협씨씨
  Nested MAC / 재귀암호화 - 해시값과 대칭키를 연결하여 다시 해시값을 생성
  HMAC (Hash MAC) / Padding - Nested MAC에 Padding 추가(ipad, opad)
  CBC-MAC / CBC - 블록모드의 CBC를 이용한 MDC 알고리즘
  CMAC / Cipher-based - CBC모드와 유사하며 N개의 평문을 n bit 암호문으로 변경
특징
  무결성 보장, 사용자 인증, 부인방지 미보장
HMAC 과정 
  키 공유 - 송수신자간 해싱키 공유 (대칭키)
  해시 생성 - 키를 이용해 원본메시지 해싱
  데이터 전송 - 생성된 MAC과 Message를 서버에 전송
  해시 생성 - 수신자는 키를 이용해 MAC을 생성
  해시 비교 - 생성된 MAC과 전달받은 MAC의 값이 같은지 비교

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
