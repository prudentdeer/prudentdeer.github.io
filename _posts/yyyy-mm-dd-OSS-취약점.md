---
title: OSS 취약점
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 소프트웨어공학]
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
      I. OSS 취약점과 대응방안
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. OSS 취약점의 정의
        </div>
        <div class="para-cntnt">
            관리적 측면
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. OSS 취약점
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. OSS 취약점의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/OSS-취약점.png" alt="OSS 취약점">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. OSS 취약점의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
              도입측면
      사용현황 부재 - 자유로운 배포특징, 현황파악 불가
      맹목적 사용 - 오픈소스 커뮤니티 맹목적 신뢰
    운영측면
      점검부재 - 패키지 형태 사용으로 점검 예외
      조치지연 - 조치주체 부재, 모호성
  기술적 측면
    취약점측면
      ZeroDay 공격 - 소스공개 특징, 공격 가능
      악성코드 배포 - 크립토재킹, 원격제어 코드
    특수성측면
      취약점 조치불가 - 오픈소스 배포사 취약점 패치 의존
      호환성 문제 - 패치 시 호환성 문제 발생
대응방안 현해스보 샌시업지
  관리적 측면
    현황파악 도구 - 오픈소스 전용 스캔도구 활용
    소스코드 해시값 - 제작자로부터 배포된 소스 확인
    SBOM - 공급망 관리 수행
    보안전문가 도입 - 유지보수 및 보안점검 수행
  기술적 측면
    샌드박스 테스트 - 악성코드 유무 확인 진행
    시큐어코딩 적용 - 2차적 저작물로 수정
    업데이트 자동화 - 오픈소스별 자동화 구현
    지능형 IPS, FW - 시그니처 기반 취약 소스코드 탐지

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
