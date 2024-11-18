---
title: 양자 취약점
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
      I. 차광암빔 트시검검
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 양자 취약점의 정의
        </div>
        <div class="para-cntnt">
            차단재전송 - 공격자가 중간에 광신호를 차단, 측정한 후 새로운 신호 전송
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 양자 취약점
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 양자 취약점의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/양자-취약점.png" alt="양자 취약점">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 양자 취약점의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            광자분리 - 단일광자 수준의 경우는 차단, 다중광자 수준인 경우 악용
  암전공격 - 공격자가 강한 펄스신호를 보내면 검출기가 측정할 수 없는 암전상태
  빔분할기 공격 - 빔분할기(BS)가 광의 파장에 의존하는 특성을 이용하는 공격 기법
구조기반
  트로이목마 - 강한펄스 전송시 입사 광신호는 시스템을 구성하는 광부품에서 반사, 시스템의 구성 유추
  시간전이 - 광검출기들의 동작시간이 외부 환경의 영향으로 다른 동작시간을 가진다는 점을 이용
  검출기불감시간 - 측정이 끝난 후 일정시간 동안 검출기가 동작하지 않는 불감시간 이용
  검출기불일치 - 광자 입사각에 따라 각 검출기의 정렬상태나, 광학계의 효율 등이 달라지는 점을 이용

대응방안
https://shinbe.tistory.com/entry/%EC%96%91%EC%9E%90%EC%95%94%ED%98%B8%ED%86%B5%EC%8B%A0

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
