---
title: 2 Channel 인증
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
      I. 다중채널 보안강화, 2 Channel 인증
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 2 Channel 인증의 정의
        </div>
        <div class="para-cntnt">
            사용자 인증을 위해 두 개의 독립적인 통신 채널을 사용하는 인증 방법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 2 Channel 인증
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 2 Channel 인증의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/2-Channel-인증.png" alt="2 Channel 인증">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 2 Channel 인증의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          절차 
  첫번째 채널 인증요청 - 사용자 정보인 지식기반 방식으로 사용자 인증을 시도 
  두번째 채널 인증요청 - 사용자에게 첫번째 채널과 다른 채널을 사용해 보안 코드를 전송 
  보안코드 입력 - 사용자는 전달받은 보안코드를 입력해 인증을 완료 
  인증확인 - 서버는 두 채널을 통해 제공된 정보를 확인하고, 두가지가 모두 확인되었을 때 인증 완료
인증요소
  첫번째 채널 - 인터넷 또는 네트워크 채널을 사용해 인증
  두번째 채널 - 추가적인 보안 인증 단계를 제공 - ARS (전화), PKI, SMS, 이메일 

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
