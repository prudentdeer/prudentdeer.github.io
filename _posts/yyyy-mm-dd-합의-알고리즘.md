---
title: 합의 알고리즘
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
      I. 블록체인 무결성보장, 합의 알고리즘
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 합의 알고리즘의 정의
        </div>
        <div class="para-cntnt">
            정보 도달에 시간차가 있는 네트워크에서 다수참가자가 통일된 결과 합의를 얻기 위한 알고리즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 합의 알고리즘
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 합의 알고리즘의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/합의-알고리즘.png" alt="합의 알고리즘">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 합의 알고리즘의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          Public 블록체인 합의 알고리즘 WSDI ABOS
  PoW - 마이닝 증명으로 블록생성, 보상, 컴퓨팅 파워기반 해시값 계산 경쟁
  PoS - 지분 크기와 생성 날짜 기반 블록 생성, PoW 에너지낭비 해결
  DPoS - 대표 노드에 검증 역할 위임, 다른 검증 노드가 대표 노드를 감시 (Delegated Proof of Stake)
  PoI - 네트워크 참여도에 따른 보상 지급, 블록체인에 기여한 노드 보상
Private 블록체인 합의 알고리즘
  PoA - 일부 참가자들 권한부여, 적은수의 노드와 높은성능 (Proof of Authority)
  PBFT - 참여노드의 다수결 투표기반 합의 (Practical Byzantine Fault Tolerance)
  PoET - 작업 경과시간 증명기반 리더 선출, 모듈형 솔루션, 위조방지 합의 (Proof of Elapsed Time)
  Sieve - 합의 형성 전 결과가 다른 경우 중지, 실행 결과 조기 탐지
Public vs Private
  접근 통제 형태 - 비허가형 &lt;&gt; 허가형
  참여 대상 - 참여 노드 제한없음 &lt;&gt; 식별된 노드만 참여
  참여 방식 - 어떤 노드든 참여 가능 &lt;&gt; 초대에 의한 참여
  보상 여부 - 참여 노드에 보상 &lt;&gt; 보상 없음
  네트워크 통제 - 별도 통제 없음 &lt;&gt; 그룹 또는 중앙 통제
  트랜잭션 확인 - 어떤 노드든 확인 가능 &lt;&gt; 참여 노드만 확인 가능
  주요 알고리즘 - PoW, PoS, DPoS, PoI, Casfer &lt;&gt; PBFT, PoET, PoA, Tendermint

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
