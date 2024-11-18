---
title: 대칭, 비대칭 암호화
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
      I. 대칭 암호화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 대칭, 비대칭 암호화의 정의
        </div>
        <div class="para-cntnt">
            암호화시 사용하는 키와 복호화시 사용하는 키가 동일한 암호화 알고리즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 대칭, 비대칭 암호화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 대칭, 비대칭 암호화의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/대칭,-비대칭-암호화.png" alt="대칭, 비대칭 암호화">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 대칭, 비대칭 암호화의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구현방식
  블록 암호화
    SPN 구조 - 샤논의 혼돈과 확산 이론 기반, S-Box, P-Box 이용 암호화되는 구조
    Feistel 구조 - 평문의 좌우를 나누어 키와 조합한 뒤 XOR 연산을 거쳐 좌우를 뒤집어주는 구조 
  스트림 암호화
비대칭 암호화
정의
  암호화시 사용하는 키와 복호화시 사용하는 키가 상이한 암호화 알고리즘
구현방식 소이타
  소인수분해
    RSA - 공개 키와 개인 키를 사용 (Rivest-Shamir-Adleman)
  이산대수
    DSA - 전자서명을 생성하는 데 사용 (Digital Signature Algorithm)
    Diffie-Hellman - 키를 교환하는 방식을 정의
  타원곡선
    ECC - 작은 키 길이로 높은 수준의 보안 (Elliptic Curve Cryptography)
대칭과 비대칭 암호화 비교
  키의수 - 단일키 &lt;&gt; 공개키, 비밀키
  속도 - 빠름 &lt;&gt; 느림
  장점 - 구현용이, 변형가능 &lt;&gt; 부인방지
  단점 - 키관리 어려움 &lt;&gt; 해독시간 소요
- 대칭키 방식은 파일 암호화 등 용도로 사용, 비대칭키 방식은 전자서명, 부인방지 용도로 사용

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
