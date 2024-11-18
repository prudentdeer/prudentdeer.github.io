---
title: SSL
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
      I. 클라이언트와 서버간 보안 프로토콜, SSL
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SSL의 정의
        </div>
        <div class="para-cntnt">
            클라이언트와 서버 통신시 응용, 전송계층 사이 보안 채널을 형성해 주는 보안 프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SSL
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SSL의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SSL.png" alt="SSL">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SSL의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          사용목적
  정보유출 방지 / 위조사이트 방지 / 데이터변조 방지 / 기업신뢰도 향상
보안기술
  상위 프로토콜 HCAR
    SSL Handshake Protocol -  서버와 클라이언트간의 상호 인증 수행
    SSL Change Cipher Spec - 협상된 암호화 방식적용 알림
    SSL Alert Protocol - 세션의 종료 또는 오류 발생시 이를 상대방에게 알림
  하위 프로토콜   
    SSL Record Protocol - 전송되는 메시지의 기밀성과 무결성 보장
운영모드 익서상
  익명 모드 - 클라이언트와 서버가 모두 공개키 인증서를 가지고 있지 않을 경우 / 개인 대 개인
  서버인증 모드 - 서버만이 공개키 인증서를 가지고 있을 경우 / 일반 홈페이지
  상호인증 모드 - 클라언트와 서버가 모두 공개키 인증서를 가지고 있을 경우 / 기관 대 기관
문제점 및 해결방안 서비트SC
  SSL의 문제점
    서버의 성능저하 - 연산 과정은 많은 계산능력을 필요로 함
    비밀키 보안문제 - 서버의 비밀키는 하드 드라이브에 저장
    트래픽 관리문제 - L4 Switch, L7 Switch 들이 기능 발휘 어려움
  해결 방안
    SSL 가속기 - 서버 성능 향상, 인증서 관리, 트래픽 관리 기능
    CDN (Contents Delivery Network) 서비스 사용
SSL 인증서 DV, OV, EV의 비교 DOE
  검증 - 도메인 &lt;&gt; 기업 &lt;&gt; 기업실체 (Extended)
  보안성 - 하 &lt;&gt; 중 &lt;&gt; 상
  비용 - 저 &lt;&gt; 중 &lt;&gt; 고
  특징 - 피싱구분 어려움 &lt;&gt; 피싱구분 어려움 &lt;&gt; 그린바 제공
- SSL 3.0 을 계승해 TLS 발전, 사실상 둘이 동일한 개념

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
