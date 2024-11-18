---
title: 파밍
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
      I. 진짜 사이트로 오인유도, 파밍
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 파밍의 정의
        </div>
        <div class="para-cntnt">
            DNS 변조 이용해 도메인 탈취하고 가짜사이트를 진짜사이트로 오인하도록 유도하는 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 파밍
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 파밍의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/파밍.png" alt="파밍">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 파밍의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  일반 인터넷 사용자에게 익숙한 인터넷 주소 강탈, 사용자의 의심 없이 중요 개인정보 노출
[공격단계] (1)위조 사이트 설치, (2) DNS 해킹, 테이블 위조 (3) DNS 조회 (4) 피해자가 가짜 사이트 접근하여 ID/PW/계좌번호 등 노출
[공격유형] DNS 주소변조 클라이언트 호스트 파일 변경, 클라이언트 DNS서버 설정 주소 변경, 등록된 도멘의 정보 변경
[대응방안] 
기술적( 도메인 기능 잠금, DNS 시스템 보안강화, SSL 확인, DNS RR 전자서명) 
관리적( 검증방안 고려, 웹 인증서 진위 여부 확인 방안 모색, OTP 사용, 신뢰사이트 등록제)

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
