---
title: 코드스멜
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
      I. 코드스멜
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 코드스멜의 정의
        </div>
        <div class="para-cntnt">
            프로그램의 오류는 아니지만 잠재적으로 문제발생 위험이 있거나 기술부채를 가지고 있는 소스코드
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 코드스멜
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 코드스멜의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/코드스멜.png" alt="코드스멜">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 코드스멜의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 중메파산
  중복된 코드 / Extract, Pullup - 똑같은 코드 구조가 두 군데 이상 있는 코드
  긴 메소드 / Extract, Decompose - 메서드의 길이가 지나치게 길고 중복된 코드가 많은 코드
  긴 파라미터리스트 / Object 변환 - 과도한 변수 리스트 사용
  산탄총 수술 / Move, Inline - 어떤 한 변경 사항이 생겼을 때 여러 모듈을 수정해야 하는 상황

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
