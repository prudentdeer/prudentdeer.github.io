---
title: DNS
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
      I. 문자형 주소를 IP 주소로 변환, DNS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DNS의 정의
        </div>
        <div class="para-cntnt">
            도메인 이름을 네트워크에서 사용하기 위해 도메인 이름을 IP 주소로 변환해주는 시스템
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DNS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DNS의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DNS.png" alt="DNS">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DNS의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 도리네리
  도메인 네임스페이스 - 네임 주소 영역을 분배, 할당, 구성하는 방식을 제공
  리소스 레코드 - 네임에 대해 필요한 인터넷 자원 정보를 맵핑하는 수단 제공
  네임서버 - 전체 인터넷 도메인 트리의 한부분을 구성하는 서버
  리졸버 - 요청 받은 도메인의 IP 정보를 조회하는 기능을 수행
  Zone 파일 : 도메인 네임과 IP주소, 다른 소스들을 포함하고 있는 리소스 레코드의 텍스트 표현
주요기능 메네로호
  Mail Server Aliasing - 해당 도메인의 메일 서버 정보 제공
  Name Resolution - URL을 IP Address로 변환
  Load Distribution - 단일 URL에 복수개의 IP 주소 설정을 통한 부하 분산
  Host Aliasing - 단일 IP Address를 보유한 호스트에 다양한 별칭 부여
Root DNS &gt; Top-Level Domain(TLD) &gt; Second-Level Domain(SLD)

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
