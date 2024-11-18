---
title: DNS 취약점 공격
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
      I. 정의
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DNS 취약점 공격의 정의
        </div>
        <div class="para-cntnt">
          1) 의도치 않은 사이트 접속 : 도메인 위·변조 시에 사용자가 의도하지 않은 사이트로 접속될 우려 발생
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DNS 취약점 공격
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DNS 취약점 공격의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DNS-취약점-공격.png" alt="DNS 취약점 공격">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DNS 취약점 공격의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          2) 장애 시 파급효과 치명적 : 도메인에 대한 기술적/보안적인 관리 허술, 가동 서비스 중단 등 우려
3) 추가 피해 : 민감한 데이터 유출과 기업의 평판 하락으로 인해 추가적인 피해 발생
[취약점공격] DNS Cache Posioning Attack, DNS 증폭 DDoS 공격
[기술적 대응방안]
서버설정(Recursion Query 제한, BIND 업데이트, Zone Transfer 제한)
시스템활용(DNSSEC 적용, KISA DDoS 대피소 활용)
[관리적 대응방안]
DNS 물리적 분리
DNS 방화벽 정책 수립
DNS 내부 운영
지속적인 DNS 보안 교육

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
