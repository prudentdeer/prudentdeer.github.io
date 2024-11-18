---
title: 영지식 증명
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
      I. Web 3.0의 초석, 영지식 증명
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 영지식 증명의 정의
        </div>
        <div class="para-cntnt">
            사전 정의된 연산의 비밀입력값 공개하지 않고 비밀입력값을 알고있음을 증명하는 암호기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 영지식 증명
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 영지식 증명의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/영지식-증명.png" alt="영지식 증명">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 영지식 증명의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          세가지 성질 완건영
  완전성 - 어떤 문장이 참일 경우, 증명자는 검증자에게 사실 납득시킬 수 있어야 한다는 성질 
  건전성 - 어떤 문장이 거짓일 경우, 어떠한 증명자라도 검증자에게 사실 납득시킬 수 없는 성질 
  영지식성 - 어떤 문장이 참일 경우, 검증자는 문장의 참 거짓 외에는 알 수 없어야 한다는 성질
증명기법 회유다
  회로특화 - 회로가 주어지면 주어진 회로에 맞는 키(SRS)를 만든다
  유니버셜 - 회로에 상관없이 키(SRS 또는 RRS)를 미리 생성
  다항식생성 - 회로의 값들 간의 관계를 순열 형태의 다항식으로 표현
유형 나타
  zk-SNARK - 영지식의 간결한 비상호작용 논증 &lt; 증명자와 검증자 상호작용이 거의, 전혀 없음 &gt;
  zk-STARK - 영지식의 간결한 투명 논증 &lt; zk-SNARK 대체 버전으로 더 빠르고 저렴 &gt;
웹 3.0 활용 로비자블
  보안
    로그인 - 패스워드 입력하지 않고 패스워드를 소유하고 있다는 것을 증명
    비밀투표 - 온라인 비밀 투표에서 사용
  프라이버시
    자격증명 - 어떤 정보도 노출하지 않고 자격이 있는지를 검증
    블록체인 - 트랜잭션의 익명성을 제공, 데이터 용량을 줄임
- 웹 3.0 토큰 이코노미 위해 디지털 자산 사생활 보호와 보안성이 같이 이뤄져야 한다
- 개인정보보호 PEC에 사용

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
