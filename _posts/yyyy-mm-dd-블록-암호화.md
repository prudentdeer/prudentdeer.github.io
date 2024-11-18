---
title: 블록 암호화
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
      I. 블록의 전치와 대체, 블록암호화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 블록 암호화의 정의
        </div>
        <div class="para-cntnt">
          &nbsp; 평문을 일정한 블록크기로 분할, S-BOX 와 P-BOX, Padding 이용 대칭키기반의 암호화 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 블록 암호화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 블록 암호화의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/블록-암호화.png" alt="블록 암호화">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 블록 암호화의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          알고리즘 에이스아리아 쉴드
  SPN 구조 - 샤논의 혼돈과 확산 이론 기반, S-Box, P-Box 이용 암호화되는 구조
    AES - 128비트 블록 DES 대체 알고리즘
    ARIA - 128비트 블록, 경량환경, 하드웨어, 대한민국 표준 알고리즘
  Feistel 구조 - 평문의 좌우를 나누어 키와 조합한 뒤 XOR 연산을 거쳐 좌우를 뒤집어주는 구조 
    SEED - 128비트 블록, 전자상거래, 무선통신
    HIGHT - 64비트 블록, 저전력 몇 경량환경
    IDEA - 64비트 블록, PGP 채택
    LEA - 128비트, IoT, 센서 경량환경
    DES - 64비트, 미국표준 알고리즘, 3DES
블록암호와 스트림 암호, 해시암호 비교
  암호단위 - 블록 &lt;&gt; 비트 &lt;&gt; 가변길이
  암호기법 - S-box, P-box &lt;&gt; XOR, 난수 &lt;&gt; 해싱 테이블
  알고리즘 - DES, AES &lt;&gt; RC4, SEA &lt;&gt; SHA256, MD5
  장점 - 기밀성, 해시함수 &lt;&gt; 빠른 속도, 에러전파 없음
  단점 - 느린 속도, 에러의 전파 &lt;&gt; 부당한 삽입과 변형
- 블록 암호화는 SW, 스트림 암호화는 HW 구현용이

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
