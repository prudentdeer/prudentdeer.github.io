---
title: XSS
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
      I. XSS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. XSS의 정의
        </div>
        <div class="para-cntnt">
            악의적인 스크립트를 삽입하여 사이트 사용방해, 정보를 특정사이트로 유출하는 공격기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. XSS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. XSS의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/XSS.png" alt="XSS">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. XSS의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 리스돔
  Reflective XSS - 공격자가 스크립트 포함 URL을 클라이언트에 노출
  Stored XSS - DB에 악성 스크립트 저장, 클라이언트 브라우저 실행
  DOM XSS - 클라이언트에서 수신받은 문서를 공격자가 조작
공격 매커니즘
  악성 스크립트 게시 - 사이트 게시판에 악성스크립트를 포함한 게시물 등록
  악성 스크립트 노출 - 악성 스크립트가 포함된 게시물의 URI를 노출
  클라이언트 게시물 실행 - 타겟은 노출된 URI를 클릭
  스크립트전송 및 시행 - 악성 스크립트가 포함된 게시물 노출 및 응답
대응 방안 쿠라입출
  쿠키정보 추출 - 중요한 정보는 쿠키에 미저장
  라이브러리 - AntiXSS 적용, Secure Coding, Validator(입력값 필터링)
  입력값 무효화 - 특수문자 필터링, White List기반 필터링
  출력값 무효화 - HTML Format 사용 금지
https://blog.skby.net/xss-cross-site-scripting/

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
