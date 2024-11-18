---
title: 스트림 암호화
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
      I. bit 단위 연속적 암호화, 스트림 암호화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 스트림 암호화의 정의
        </div>
        <div class="para-cntnt">
            평문과 동일한 길이의 키스트림 수열을 생성하여, 난수적용, XOR연산을 통한 암호화 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 스트림 암호화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 스트림 암호화의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/스트림-암호화.png" alt="스트림 암호화">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 스트림 암호화의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  빠른 속도, 낮은 오류율
알고리즘 알씨살차
  RC4 - SSL/TLS 1.1~1.2 사용 / 바이트 단위로 연산하는 키 크기가 가변인 스트림 암호
  SEA - XOR 기반 암호체계 / 32비트 컴퓨터 고속 스트림 암호 (Software-optimized Encryption Algorithm)
  Salsa20 - 20라운드 구성 / 256비트 키와 64비트 블록 크기를 사용
  ChaCha20 - TLS 1.3 / Salsa20 기반 256비트 키와 64비트 블록 크기 
블록암호와 스트림 암호, 해시암호 비교
  암호단위 - 블록 &lt;&gt; 비트 &lt;&gt; 가변길이
  암호기법 - S-box, P-box &lt;&gt; XOR, 난수 &lt;&gt; 해싱 테이블
  알고리즘 - DES, AES &lt;&gt; RC4, SEA &lt;&gt; SHA256, MD5
  장점 : 기밀성, 해시함수 &lt;&gt; 빠른 속도, 에러전파 없음
  단점 : 느린 속도, 에러의 전파 &lt;&gt; 부당한 삽입과 변형
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
