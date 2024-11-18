---
title: Cache Flush/Cache Clean
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
      I. [Clean] D bit, V bit clear. Data mem으로 write, 메모리=Cache data
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Cache Flush/Cache Clean의 정의
        </div>
        <div class="para-cntnt">
          [목적] 캐시 일치성 문제 해결
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Cache Flush/Cache Clean
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Cache Flush/Cache Clean의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Cache-Flush,Cache-Clean.png" alt="Cache Flush/Cache Clean">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Cache Flush/Cache Clean의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          [구성요소] Memory(폰노이만구조,저속), Cache(고속), Flush(I-Cache,D-Cache중
하나 reset), Invalidate(Control bit 무효화 설정), Clean(cache의 dirty data를
memory로 강제로 WB,D-Cache clean)
* WB에서는 Flush전 clean진행

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
