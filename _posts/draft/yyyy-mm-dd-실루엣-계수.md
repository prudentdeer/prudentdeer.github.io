---
title: 실루엣 계수
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 인공지능]
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
      I. 실루엣계수
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 실루엣 계수의 정의
        </div>
        <div class="para-cntnt">
            클러스터링을 평가하기 위해 군집 내 데이터 응집정도와 군집간 분리정도 분석한 계수
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 실루엣 계수
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 실루엣 계수의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/실루엣-계수.png" alt="실루엣 계수">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 실루엣 계수의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          실루엣계수 -1~1
  1 = 'clear-cut' 클러스터 
  0 = 두 군집 간 거리가 거의 비슷한 경우
  -1 = 오히려 이웃 클러스터에 더 가까운 경우 
실루엣계수 평균값 0~1
  Clear-cut / 1에 근접 - 1에 가까운 평균값을 가지는 클러스터, 
  Weak 클러스터 / 0에 근접 - 0에 가까운 값을 가지는 클러스터
https://studying-haeung.tistory.com/10

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
