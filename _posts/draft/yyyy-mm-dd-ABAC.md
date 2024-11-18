---
title: ABAC
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
      I. 제로트러스트 및 클라우드 접근통제 정책, ABAC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ABAC의 정의
        </div>
        <div class="para-cntnt">
            속성기반으로 환경을 동적으로 분석하여 접근 사용자 및 시스템에 권한을 부여하는 접근통제 정책
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. ABAC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. ABAC의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/ABAC.png" alt="ABAC">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. ABAC의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 주객환정특
  속성
    주체 - 이름, 역할, 포지션 등
    객체/자원 - file, device, table, record, process, program, 시스템 기능, 웹서비스 등
    환경속성 - 운영, 기술, 상황, 환경(ex.현재 날짜, 시간 등)
  정책
    정책 - 조직내 허용된 행동을 통제하는 집합
    특권 - 객체 보호의 한도 내 주체가 허가 받은 행위 표현
ABAC 과 RBAC 의 비교
  정책 - 속성기반 정의 &lt;&gt; 역할기반 정의
  장점 - 구체적, 세분화 규칙 &lt;&gt; 단순성
  단점 - 변수 정의 및 규칙 구성 노력 &lt;&gt; 역할 폭발 (지속적 역할 추가에 따른 관리 어려움)

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
