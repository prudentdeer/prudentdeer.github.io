---
title: 디피헬만 키교환
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
      I. 암호화 키 교환 메커니즘, Diffie-Hellman
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 디피헬만 키교환의 정의
        </div>
        <div class="para-cntnt">
            송신자와 수신자가 암호화되지 않은 통신망을 통해 안전하게 키를 공유할 수 있는 키교환 알고리즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 디피헬만 키교환
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 디피헬만 키교환의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/디피헬만-키교환.png" alt="디피헬만 키교환">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 디피헬만 키교환의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  공개키 사용, 이산대수 어려움, 비밀키 사용
알고리즘 절차
  1  Allice가 소수 p, 그리고 1 부터 p-1까지의 정수 g를 선택하여 사전에 Bob과 공유
  2  Allice가 정수 a를 선택, 이 정수는 외부에 공개되지 않으며 Bob 또한 알 수 없음
  3  Allice가 A=ga mod p, 즉 ga 를 p로 나눈 나머지를 계산
  4  Bob이 마찬가지로 정수 b를 선택, B=gb mod p를 계산
  5  Allice와 Bob이 서로에게 A와 B를 전송
  6  Allice가 Ba mod p를 Bob이 Ab mod p를 계산
  7  마지막 단계에서 Ba = (gb)a=gab, Ab=(ga)b=Gab 이며, 따라서 Allice와 Bob은 gab mod p라는 공통의 비밀키를 공유
취약점, 대응방안
  MITM / 개인, 공개키 암호화 - RSA 알고리즘 적용 보안강화
  Shor 알고리즘 / 양자내성암호 - 

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
