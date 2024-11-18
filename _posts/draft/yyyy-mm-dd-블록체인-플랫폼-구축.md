---
title: 블록체인 플랫폼 구축
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
      I. 성능측면 고려사항 확성합커
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 블록체인 플랫폼 구축의 정의
        </div>
        <div class="para-cntnt">
            성능저하 / 라이트닝 네트워크 - 주 거래는 on-chain, 나머지는 off-chain
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 블록체인 플랫폼 구축
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 블록체인 플랫폼 구축의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/블록체인-플랫폼-구축.png" alt="블록체인 플랫폼 구축">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 블록체인 플랫폼 구축의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            합의알고리즘 / 배칭거래 - 거래 한번에 묶어서합의 진행 (Batching Transaction)
  커스터마이징 / Private 블록체인 - 엔터프라이즈 환경에 맞게 커스터마이징
보안측면 고려사항 취비소개
  취약한 키관리 / 정책, 가이드준수 – 기관에서 발행한 보안가이드 준수
  비정상거래 / 참여자 모니터링 - 유효하지 않은 거래 차단 및 합의 과정 모니터링
  S/W 취약점 / 시큐어 코딩 - 악성코드여부 확인하여 검증
  개인정보침해 / 최소한의 정보 - 무결성 확인에 필요한 최소정보만 유지
플랫폼 구축 위한 BaaS 
  정의 - 블록체인 기술 인프라를 지원하여 빠르게 블록체인을 도입할 수 있도록하는 클라우드 서비스
  지원서비스 멀통이상
    멀티클라우드 - 사용자가 원하는 클라우드 환경 상 블록체인을 설치
    통합개발환경 - 스마트 컨트랙트 개발 및 배포 환경과 운영 환경 제공
    이종체인 연결 - 다른 블록체인 프로토콜과 서로 연결하여 사용
    블록상태 조회 - 블록생성 현황과 트랜잭션 목록 및 내역 확인
    블록체인 프로토콜 - 목적과 용도에 따라 사용자가 자유롭게 선택
    합의 메커니즘 - 서비스의 운영 방법과 구조, 정책에 따라 선택
    대량 트랜잭션 - 대용량 트랜잭션을 안정적으로 처리할 수 있는 처리 기능
    기술지원 - 기술지원 및 원격 지원부터 유료 컨설팅

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
