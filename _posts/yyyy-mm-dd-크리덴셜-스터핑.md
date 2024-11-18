---
title: 크리덴셜 스터핑
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
      I. 계정탈취와 무작위 대입, 크리덴셜 스터핑
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 크리덴셜 스터핑의 정의
        </div>
        <div class="para-cntnt">
            탈취한 로그인 자격증명을 이용해 다른 사이트에 봇넷기반 Bruteforce 로그인 시도 공격기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 크리덴셜 스터핑
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 크리덴셜 스터핑의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/크리덴셜-스터핑.png" alt="크리덴셜 스터핑">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 크리덴셜 스터핑의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          공격절차 수봇공반
  수집 / 인포스틸러, 다크웹 구매 - 악성코드를 이용하여 불특정 다수의 개인정보, 고객정보 탈취
  봇넷 / 로그인 봇넷,  봇넷 코디네이터 - 봇넷 형성
  공격 / Brute force - 개인정보를 구매한 해커B는 크리덴셜 스터핑 공격 실행
  반복 / 다크웹판매, 공격 반복 - 다크웹 통한 거래 및 공격 반복
대응방안 오비멀패
  개인
    OSMU 지양 - 한 가지의 ID와 비밀번호 조합을 반복적으로 사용 지양
    비밀번호 주기적 변경 - 로그인 정보 주기적 변경 통해 2차 피해 방어
  기업
    패스키 - 종단 간 암호화 통해 모든과정 암호화
    Mulfi Factor 인증 - 비밀번호 외에도 문자인증, OTP인증 등의 다중인증(Multi�Factor)옵션 도입
- 봇 스크리닝 통한 자동화 봇 차단 필요
- 현금화, 공유, 악용, 리패키징 4단계 후 폐기

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
