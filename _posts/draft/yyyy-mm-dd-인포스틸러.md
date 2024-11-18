---
title: 인포스틸러
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
      I. 유출형 악성코드, 인포스틸러의 개념
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 인포스틸러의 정의
        </div>
        <div class="para-cntnt">
            브라우저, 이메일 등 저장된 사용자 정보 탈취, 2차공격 위한 정보 유출형 악성코드
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 인포스틸러
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 인포스틸러의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/인포스틸러.png" alt="인포스틸러">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 인포스틸러의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            계정, 쿠키, 카드, 자동완성, 히스토리 계쿠카자히
공격절차 악개이 불스정탈추금
  악성코드 유포
    불법 프로그램 - exploit 설치, 활성화
    스팸 메일 - 첨부파일 통한 설치
  개인정보 수집
    정보수집 - 계정정보, 쿠키, 카드정보, 히스토리, 자동완성
    탈취전송 - 데이터 수집, 전송
  2차공격
    추가감염 - 랜섬웨어, 악성코드 추가설치
    금전피해 - 광범위 정보탈취로 금전피해
대응방안 (정보보안 담당자 입장)
  관리적 대응방안
    보안정책수립
    망 분리
    정기적 교육 - 비밀번호 웹브라우저 저장 자제 및 비밀번호 주기적 변경 
  기술적 대응방안
    최신업데이트
    백신프로그램 
    캐시자동삭제
인포스틸러와 크리덴셜스터핑 비교
  1차공격 - 사용자 정보탈취 &lt;&gt; 로그인 자격증명 탈취
  탈취 - 계쿠카자히 &lt;&gt; 계정, 비밀번호, 세션
  2차공격 - 랜섬웨어, 백도어 &lt;&gt; 무차별 대입, Bruteforce
  예방 - 안티바이러스 , 방화벽 &lt;&gt; 멀티팩터 인증
- 인포스틸러 유출보다 이로 인한 2차 피해가 심각

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
