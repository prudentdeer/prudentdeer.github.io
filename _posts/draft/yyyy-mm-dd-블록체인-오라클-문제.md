---
title: 블록체인 오라클 문제
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
      I. 블록체인 오라클 문제
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 블록체인 오라클 문제의 정의
        </div>
        <div class="para-cntnt">
            Off-Chain 데이터를 On-Chain으로 가져올 때 오류, 위변조로 인해 신뢰성이 훼손되는 현상
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 블록체인 오라클 문제
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 블록체인 오라클 문제의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/블록체인-오라클-문제.png" alt="블록체인 오라클 문제">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 블록체인 오라클 문제의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          문제의 유형 하소아
  하드웨어 오라클 - 외부 변화를 감지해서 데이터를 송신하는 센서 / 장치 오작동, 부정확한 측정
  소프트웨어 오라클 - 온라인 상의 신뢰할 수 있는 채널로부터 데이터를 가져오는 것 / 자료 수집 봇이나 AI등의 잘못된 판단
  아웃바운드 오라클 - 거래 데이터를 외부로 전송 / 블록체인의 잘못된정보를 외부로 전송
해결방안 투중간
  투표 / POW. POS - 암호화폐 소유자들이 투표를 통해 합의
  중앙값 / 메이커, 어거 - 데이터 중 중앙값을 선택
  중간자 / 오라클, 체인링크 - 실세계와 블록체인 사이에 신뢰할 수 있는 중간자
디파이에서의 오라클 활용 써퍼
  써드파티 오라클 / 제3자 - 제 3자의 검증자가 오프체인 검증, 온체인 기록
  퍼스트파티 오라클 / 없음 - 검증자 없이 데이터를 제공하는 주체가 기록
-  크립토 이코노미가 제대로 작동하려면, 오라클 문제 해결필요

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
