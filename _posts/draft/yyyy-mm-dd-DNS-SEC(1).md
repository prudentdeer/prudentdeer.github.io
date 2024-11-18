---
title: DNS SEC
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
      I. DNS의 위변조 방지, DNSSEC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DNS SEC의 정의
        </div>
        <div class="para-cntnt">
            DNS 위, 변조 차단을 위해 공개키 암호화 방식의 전자서명 기술을 적용한 보안강화 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DNS SEC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DNS SEC의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DNS-SEC.png" alt="DNS SEC">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DNS SEC의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          DNS 보안 취약점 
  캐시포이즈닝 : DNS 정보를 위/변조하는 공격, DNS 프로토콜 자체 취약성으로 DNS 캐시에 저장된 쿼리 위/변조
  패킷가로채기 : DNS 질의/응답 과정 중의 패킷을 가로채 정보 위/변조
  위장공격 : 루트 네임서버, KR 네임서버 등 정보제공 DNS로 위장
구성요소
  DNSKEY : 도메인 존의 공개키 데이터를 저장하여 제공하기 위한 RR
  RRSIG : 존 안에 있는 RRSet에 대한 개인 키의 전자 서명한 결과값을 갖는 RR
  DS : DNS 고유의 위임체계에 따라 보안 측면의 인증된 위임체계를 구성하기 위한 데이터를 저장하는 RR
  NSEC/NSEC3 : DNS 데이터 부재 인증을 위해 정의된 RR

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
