---
title: 신뢰성 테스트
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
      I. 핵심목표
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 신뢰성 테스트의 정의
        </div>
        <div class="para-cntnt">
            회복능력 검증 – 오류 발생 시 신속하고 정확하게 복구되는지 확인
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 신뢰성 테스트
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 신뢰성 테스트의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/신뢰성-테스트.png" alt="신뢰성 테스트">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 신뢰성 테스트의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            성능 유지 – 지속적인 사용 및 부하 상황에서 성능저하 없이 작동하는지 확인
세부활동
  부하 테스트 – 시스템에 예상되는 최대 부하를 가해 성능 저하 또는 오류발생 테스트
  스트레스 테스트 – 시스템에 과도한 부하 또는 오류상황에 노출시켜 시스템의 한계점 테스트
  지속 테스트 – 시스템을 장기간 실행하면서 성능저하 또는 오류발생 테스트
  회복 테스트 – 시스템의 오류 발생 이후 정상 상태로 복구되는지 테스트

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
