---
title: SW 아키텍처스타일, 패턴
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 소프트웨어공학]
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
      I. 재사용성 증가 위한, 아키텍처 스타일
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SW 아키텍처스타일, 패턴의 정의
        </div>
        <div class="para-cntnt">
            SW 아키텍처의 반복, 공통 문제 해결을 위해 일반적, 재사용가능한 해결책을 규격화한 설계패턴
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SW 아키텍처스타일, 패턴
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SW 아키텍처스타일, 패턴의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SW-아키텍처스타일,-패턴.png" alt="SW 아키텍처스타일, 패턴">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SW 아키텍처스타일, 패턴의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            디자인 패턴 &gt; 아키텍처 패턴 &gt; 아키텍처 스타일
유형 클레브마피 파이블인 M
  Client Server / 이메일 - 한 서버, 다수 클라이언트 / TCP-IP 이용
  Layered / ,  - 계층끼리 상호작용 / N티어 / 계층별 추상화 / 표준화 쉬움
  Broker / 카프카 - 객체의 동적변경, 할당 가능 / 리디렉션
  Master Slave / DB, REPLICA - 슬레이브 마스터 동기화 / 데이터베이스 활용
  Peer to Peer / 파일공유 - 각 노드 Server, Client 둘다 가능
  Pipe-Filter / 컴파일러 - 데이터 스트림이용 동시성 처리 / 확장성 / 재사용성
  Event-Bus / 알림서비스 - 이벤트 메시지를 발행(Publish)하면, 해당 채널을 구독(Subscribe)
  Blackboard / 음성인식 - 모든 컴포넌트들이 공유 데이터 저장소와 블랙보드 컴포넌트에 접근이 가능
  Interpreter / SQL - 특정 언어 작성된 프로그램 해석
  MSA - 시스템을 여러 개의 독립된 서비스로 분할 후 해당 서비스들을 조합, REST API 이용해 통신
https://mingrammer.com/translation-10-common-software-architectural-patterns-in-a-nutshell/

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
