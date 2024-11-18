---
title: 라이트닝 네트워크
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
      I. 블록체인 거래속도 확장, 라이트닝 네트워크
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 라이트닝 네트워크의 정의
        </div>
        <div class="para-cntnt">
            처리속도 향상을 위해 개별거래를 Off-chain 처리하고 결과만 On-chain 기록하는 프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 라이트닝 네트워크
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 라이트닝 네트워크의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/라이트닝-네트워크.png" alt="라이트닝 네트워크">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 라이트닝 네트워크의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  빠른속도, 확장성, 낮은 수수료
프로세스
  Funding 트랜젝션 생성 / On chain - 외부 결제채널 생성 시점에 블록체인 상에 기록하는 트랜젝션
  Commitment 트랜젝션 생성 / Off chain - 외부 결제채널에 기록되는 거래당사자간 대량의 소액거래 트랜젝션
  Commitment 트랜젝션 서명 / Off chain - Funding 트랜젝션에 다시 기록시 수행하는 거래당사자간 서명
  Funding 트랜젝션에 통보 / On chain - Commitment 트랜젝션 내용을 Funding 트랜젝션에 통보, 기록
문제점과 해결방안
  문제점 - Off chain 조작 / 합의과정없는 거래기록 조작후 On chain에 커밋
  해결방안 - Timestamp 사용 / On chain에 기록된지 얼마 안된 트랜젝션 취소가능

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
