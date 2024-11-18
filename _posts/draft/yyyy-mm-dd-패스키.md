---
title: 패스키
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
      I. 비밀번호 없는 로그인 방식, 패스키
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 패스키의 정의
        </div>
        <div class="para-cntnt">
            비밀번호 없이 WebAuthn 기반 서버 공개키와 기기의 개인 키를 연결하는 로그인 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 패스키
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 패스키의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/패스키.png" alt="패스키">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 패스키의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          기술요소 어클리 애아크메
  인증
    Authenticator - 인증 대상 개인키를 생성/저장
    Client application - 사용자의 패스키 인증 및 등록 절차 수행
    Relying party - 요청한 리소스 접근 여부 결정 
  서비스/저장소
    Application layer - 자격 증명 저장소 참조하여 패스키 등록/인증)
    Identity provider - 인증 토큰(OAuth2) 발급 서비스
    Credential repository - 자격 증명(공개키) 저장소
    Metadata repository - 등록된 인증자의 제조사와 모델 식별
패스키와 지식기반 비교
  암호추측 - O &lt;&gt; X
  암호재활용 - O &lt;&gt; X
  기기탈취 - O &lt;&gt; O
  피싱 - O &lt;&gt; X
  유출 - O &lt;&gt; X
- 패스키는 FIDO Alliance에서 표준화, Google, Microsoft, Apple, 빅테크 기업을 시작으로 적용 확대
- FIDO 1.0과 FIDO 2는 모두 기기를 잃어버리면 새로운 키를 발급받아야 한다는 단점
- 사용자가 디바이스를 잃어버려도 계정 복구가 쉽고 다양한 디바이스에서 하나의 계정을 동시에 사용할 수 있도록 나온 기술이 바로 패스키

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
