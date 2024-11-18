---
title: 패딩
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
      I. 블록암호화 알고리즘의 패딩
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 패딩의 정의
        </div>
        <div class="para-cntnt">
            암호화할 데이터의 길이가 블록의 길이보다 작을 경우 빈 부분을 채워주는 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 패딩
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 패딩의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/패딩.png" alt="패딩">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 패딩의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형
  비트단위 
    비트패딩 - 패딩이 필요한 부분은 0으로 채우되, 최상위 비트는 1로 채우는 방식 
  바이트단위 
    ANSI X.923 - 나머지 값을 0으로 채우고, 마지막은 모자란 바이트 개수를 넣는 방식 
    ISO 10126 - 나머지 값을 랜덤으로 채우고, 마지막은 모자란 바이트 개수를 넣는 방식 
    PKCS5 - 패딩이 필요한 바이트 숫자값으로 패딩하는 방식
    PKCS7 - PKCS5를 16 byte까지의 블록 사이즈에 대해서 동작하도록 정의된 방식 
    제로패딩 - 패딩이 필요한 바이트를 모두 0으로 채우는 방식

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
