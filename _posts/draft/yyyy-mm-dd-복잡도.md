---
title: 복잡도
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 알고리즘]
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
      I. 시간복잡도
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 복잡도의 정의
        </div>
        <div class="para-cntnt">
            알고리즘의 성능과 효율 평가하기 위해 입력 데이터에 따라 필요한 연산의 횟수
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 복잡도
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 복잡도의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/복잡도.png" alt="복잡도">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 복잡도의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          표현 메세오
  Best / Ω, 빅오메가 - 최상일때 기준으로 평가
  Avg / Θ, 빅세타 - 빅오, 빅오메가 둘 다를 포함
  Worst / O, 빅오 - 최악일때 기준으로 평가
- 수행 시간은 실행환경에 따라 다르게 측정되기 때문에 연산횟수로 판별
- 알고리즘이 복잡해질수록 평균 구하기가 어려워 최악성능을 파악

공간복잡도
정의
  알고리즘의 성능과 효율 평가하기 위해 입력 데이터에 따른 필요한 메모리 공간
표현 고가
  고정공간 C - 알고리즘 무관한 공간 / 코드저장, 단순 변수와 상수
  가변공간 Sp(n) - 알고리즘 실행과 관련 / 동적 필요공간
  계산 = C + Sp(n)

시간복잡도, 공간복잡도 비교
  목적 - 연산횟수 측정 &lt;&gt; 메모리사용 측정
  수식 - Big-O 표기 &lt;&gt;  고정공간 + 가변공간
  기준 - 작을수록 효율 &lt;&gt; 적을수록 효율
- 성능평가시 시공간 복잡도, 최악케이스 고려

https://yoongrammer.tistory.com/79

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
