---
title: 머클트리
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
      I. 블록체인의 거래를 묶어주는 머클트리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 머클트리의 정의
        </div>
        <div class="para-cntnt">
            거래의 유효성 검증을 위해 블록 내 저장된 거래의 해시 값을 이진트리 형태로 구성한 트리
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 머클트리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 머클트리의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/머클트리.png" alt="머클트리">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 머클트리의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  이진트리 구조 : 거래의 해시 값을 두 개씩 묶어 이진트리 구성, 특정 거래를 찾는 경로 단순
  동일한 노드 크기 : SHA256 해시함수를 사용해 모든 노드에 저장되는 값이 32바이트로 동일
  쇄도효과 : 거래정보가 변조되면 해당 거래부터 머클 루트까지 경로 내 모든 해시 값이 변경
구성요소 경루샤풀라
  트리
    머클 루트 - 머클트리 루트로 모든거래 요약
    머클 경로 - 머클 루트부터 특정 거래의 경로
  암호화
    SHA-256 - 암호화 위해 SHA-256 해시함수 사용
  노드
    풀 노드 - 제네시스 블록 ~ 현재 블록체인 전체를 유지하는 노드
    라이트 노드 - 일부 블록만 소유, 풀 노드에게서 필요한 정보만을 받아서 유지하는 노드
활용
  비트코인 - 이전 트랜젝션 데이터를 묶어 해시한 값 보유
  이더리움
  Bit torrent - 파일전송시 파일분할후 머클트리로 전송
  Git - branch 와 merge는 이전상태를 자식으로 갖는 머클트리

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
