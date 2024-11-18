---
title: 몽키테스트
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
      I. 몽키테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 몽키테스트의 정의
        </div>
        <div class="para-cntnt">
            전체 시스템 대상 컴포넌트 무작위 터치, 클릭 이벤트 발생시켜 오류발생 확인하는 테스트
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 몽키테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 몽키테스트의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/몽키테스트.png" alt="몽키테스트">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 몽키테스트의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          몽키테스트 회귀테스트 비교
  목적 - 예상못한 오류발견 &lt;&gt; 수정에 따른 영향도 확인
  대상 - 에뮬레이터, 디바이스 &lt;&gt; 수정 대상 소프트웨어 전체
  수행 시기 - 초기모델 개발단계 &lt;&gt; 운영 환경 수정 발생 시
  절차 - 스크립트 작성 -&gt; 실행 -&gt; 오류 검출 - 수정 발생 -&gt; 영향도 분석 -&gt; 실행
  추적성 - 추적 불가 &lt;&gt; 추적 가능
  완료 시점 - 일정시간 수행 &lt;&gt; 대상, 점검 완료 시
  도구 - monkeyrunner - Selenium, QTP, RFT

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
