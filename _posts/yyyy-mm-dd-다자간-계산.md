---
title: 다자간 계산
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
      I. 블록체인 개인키 보관기술, MPC 
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 다자간 계산의 정의
        </div>
        <div class="para-cntnt">
            둘 이상의 참여자가 각자의 비밀 데이터를 보유한 채로 공동의 계산 목표 달성하는 암호학적 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 다자간 계산
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 다자간 계산의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/다자간-계산.png" alt="다자간 계산">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 다자간 계산의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          원리
  비밀유지 – 각 참여자는 자신의 데이터를 비밀로 유지
  공동계산 – 참여자들은 자신의 데이터를 이용하여 공동으로 어떤 함수를 계산
  결과공유 – 계산된 결과는 참여자들 사이에서 공유
특징
  프라이버시 보호 – 자신의 데이터를 공개하지 않고도 공동의 계산이 가능
  보안성 – 외부 공격자나 비협조적인 참여자로부터 데이터를 보호함
  정확성 – 계산 결과는 모든 참여자의 데이터가 정확하게 고려되어 산출
  분산된 신뢰 – 중앙 집중형 신뢰 기관이 없어도 참여자들 간에 신뢰를 구축할 수 있음
기술유형
  비밀분할 기반
    비밀분할 - 여러 조각으로 나누고, 일정 수 이상의 조각이 모여야만 비밀을 복원
    베이버트리플 - 데이터 공개 없이 여러 참가자가 공동으로 데이터를 계산
  회로 기반
    Garbled Circuits - Boolean 회로를 암호화하여, 입력값을 숨긴 채 계산
    Oblivious Transfer - 송신자가 어떤 정보를 수신자에게 전달했는지 수신자만 알 수 있게 하는 프로토콜
MPC 기반 인증서비스
  혼란회로 / 보안계산 - 두 참여자가 비밀번호 일치여부 판단
  비밀분산 / 키관리 - 비밀 금고의 잠금 코드를 여러 관리자에게 분산
  동형암호화 / 데이터분석 - 동형 암호화를 사용하여 고객의 개인정보를 보호
  무지전송 / 보안투표 - 투표 관리자는 누구를 선택했는지 알 수 없음

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
