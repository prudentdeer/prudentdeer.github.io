---
title: 서비스 프리미티브
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 네트워크]
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
      I. 레이어 상호동작 규정, 서비스 프리미티브
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 서비스 프리미티브의 정의
        </div>
        <div class="para-cntnt">
            OSI 7, TCP/IP 의 상위계층과 하위계층의 서비스 요구, 지시, 응답, 확인 통한 계층 간 통신 기능
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 서비스 프리미티브
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 서비스 프리미티브의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/서비스-프리미티브.png" alt="서비스 프리미티브">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 서비스 프리미티브의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          신호종류 요지응확
  요구 / 서비스 이용 – 서비스의 개시 요구, N+1 &gt; N 
  지시 / 서비스 제공 – 서비스 개시 됨 표시, N &gt; N+1 
  응답 / 서비스 이용 – 지시에 의해 서비스 수행 표시, N+1 &gt; N 
  확인 / 서비스 제공 – 응답에 의해 서비스 수행 표시, N &gt; N+1
연결형 프리미티브 유형 커데디
  Connect - 연결 설정 프리미티브
  Data - 데이터 전송 프리미티브
  Disconnect - 연결 해제 프리미티브

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
