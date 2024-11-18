---
title: 베이즈정리
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 확률과통계]
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
      I. 베이즈정리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 베이즈정리의 정의
        </div>
        <div class="para-cntnt">
            두 확률 변수의 경험기반 사전확률과 우도기반 사후확률 사이의 관계를 나타내는 정리 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 베이즈정리
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 베이즈정리의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/베이즈정리.png" alt="베이즈정리">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 베이즈정리의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          전제조건 
  증상에 해당하는 n개의 요소 사건 A1, A2, An이 서로 배반임
수식
  사전확률 P(Ai) - 관측자가 이미 알고 있는 사건의 확률, P(Ai) 
  우도 P(B|Ai) - 이미 알고 있는 사건(Ai)이 발생했다는 조건하에 다른 사건(B)이 발생할 확률 
  사후확률 P(Ai|B) - 사전확률P(Ai)과 우도 P(B|Ai) 를 통해 알게 되는 조건부 확률
계산
  문제 
    공장 A, B 가 책상을 각각 전체의 70%, 30% 씩 생산하고 있다. 
    이때 각 공장에서 생산한 제품의 불량률은 6%, 2% 이다. 
    어떤 소비자가 구입한 책상이 불량품이었을때 이 불량품이 공장 B 의 제품일 확률을 구하시오 
  사전확률
    P(A) = 0.7, P(B) = 0.3 
  우도 
    P(F|A) = 0.06, P(F|B) = 0.02 
  사후확률 
    𝑷(𝑩|𝑭) = 𝑷(𝑭|𝑩)𝑷(𝑩) / 𝑷(𝑭) = 𝑷(𝑭|𝑩)𝑷(𝑩) / 𝑷(𝑭|𝑩)𝑷(𝑩) + 𝑷(𝑭|𝑨)𝑷(𝑨)
     = 𝟎.𝟑×𝟎.𝟎𝟐 / 𝟎.𝟑×𝟎.𝟎𝟐 + 𝟎.𝟕×𝟎.𝟎𝟔
     = 12.5% 
  결론 
    불량품이 공장 B의 제품일 확률 = 12.5%

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
