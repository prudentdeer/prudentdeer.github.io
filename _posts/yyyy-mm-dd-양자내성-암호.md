---
title: 양자내성 암호
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
      I. Q-Day 대비 PQC, 양자내성암호
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 양자내성 암호의 정의
        </div>
        <div class="para-cntnt">
            기존암호 &gt; (양자역학 원리) &gt; 양자암호 &gt; (양자컴퓨터 대응) &gt; 양자내성암호화
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 양자내성 암호
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 양자내성 암호의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/양자내성-암호.png" alt="양자내성 암호">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 양자내성 암호의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          정의 (PQC)
  양자컴퓨팅 암호해독 대응위해 기존 Shore, grover 대체위한 공개키 방식의 암호 알고리즘
알고리즘 다코격아해
  다변수기반 암호 / 작은 서명, 큰 키 사이즈 - 다변수함수 문제의 어려움에 기반
  코드기반 암호 / 빠른 암, 복호화 - 선형 코드를 디코딩하는 어려움에 기반  
  격자기반 / 다양한환경 지원 - 수백차원 격자 계산문제의 어려움에 기반, 변수설정 어려움
  아이소제니 기반 / 구현의 편리성 - 순서가 같은 두 타원곡선 사이 아이소제니를 구하는 어려움에 기반, 연산속도 느림
  해시 기반 / 안전성 증명 - 해시 함수의 안전성을 기반으로 한 전자 서명 시스템, 큰 서명사이즈
양자내성암호화 동향
  국내 / K-암호체계 개발 - 2035년까지 국가 암호체계를 한국형 양자내성암호로 전환
  국외 / PQC 알고리즘선정 - 현재 3종까지 선정, 2024년까지 4종 선정 예정  
NIST 최종후보 암전 카딜팔스
  암호화/키 교환
    크리스탈 카이버 - FIPS 203, 격자기반, 보안, 성능우수, 일반적 웹 암호 SSL에 사용
  전자서명
    크리스탈 딜리시움 - FIPS 204, 격자기반, 보안, 성능우수, 우선순위 알고리즘
    팔콘 - 격자기반, 성능우수, 서명길이작음
    스핑크스+ - FIPS 205, 해시함수기반, 크고 속도 느림, 
- 양자 컴퓨터가 기존 암호화 알고리즘을 깨는 Q-데이 대비

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
