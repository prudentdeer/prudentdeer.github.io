---
title: 암달의 법칙(Amdahl’s Law)
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 컴퓨터구조]
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
      I. [정의] 프로그램은 병렬처리가 가능한 부분과 불가능한 순차적인 부분으로 구성되므로, 프로세서를 병렬화 시켜도 더 이상 성능이 향상되지 않는 한계가 존재 한다는 법칙
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 암달의 법칙(Amdahl’s Law)의 정의
        </div>
        <div class="para-cntnt">
          시스템 향상도(K) = 1 / ( (1-t) + t/n ), n : 향상배수, t : 향상 가능 부분
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 암달의 법칙(Amdahl’s Law)
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 암달의 법칙(Amdahl’s Law)의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/암달의-법칙(Amdahl’s-Law).png" alt="암달의 법칙(Amdahl’s Law)">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 암달의 법칙(Amdahl’s Law)의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          
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
