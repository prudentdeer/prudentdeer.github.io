---
title: 회귀 테스트
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
      I. Secondary 결함확인, 회귀테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 회귀 테스트의 정의
        </div>
        <div class="para-cntnt">
            오류를 제거하거나 수정한 시스템에서 이로인해 새로 유입된 오류가 없는지 확인하는 반복 테스트
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 회귀 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 회귀 테스트의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/회귀-테스트.png" alt="회귀 테스트">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 회귀 테스트의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          필요성
  결함조치 확인, 신규오류 확인, 정합성 확인
상세설명 사회사문 리셀프
  사전준비 - 테스트 수행전 확인사항 체크(스모크 진행가능), 변경된 각 모듈의 통합 및 배포 수정까지 빌드 실시
  회귀테스트수행 - TC Lib같은 도구로 회귀테스트 수행. 반복 및 제약부하 환경에서 성능테스트
  사후검증 - 기존 단위테스트의 회귀테스트는 repository에 저장
  문서화 - 변경된 기능 및 시나리오 감안한 테스트 절차 최신화
Retest All vs Selective Test vs Priority Test
  수행방법 : 테스트 케이스 전부 &lt;&gt; 영향범위 결정 &lt;&gt; 핵심기능 위주
  적용분야 : 고위험 시스템 &lt;&gt; 일반 시스템 &lt;&gt; 저위험 테스트
  장점 : 높은 커버리지 &lt;&gt; 일반 시스템 &lt;&gt; 저위험 시스템
  단점 : 높은 비용 &lt;&gt; 범위선정 어려움 &lt;&gt; 기준 모호

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
