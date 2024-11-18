---
title: 동형암호
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
      I. 복호화 없는 연산수행, 동형암호
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 동형암호의 정의
        </div>
        <div class="para-cntnt">
            정보를 암호화한 상태에서 연산을 했을 때, 암호화하지 않은 연산 결과와 동일한 4세대 암호체계
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 동형암호
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 동형암호의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/동형암호.png" alt="동형암호">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 동형암호의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징 격서다보
  격자기반 - 양자컴퓨터도 찾아내기힘든 수백차원 격자기반
  서킷 프라이버시 - 연산 진행 시 연산에 대한 정보를 알지 못하는 성질
  다중도약 동형성 - 생성된 암호문이 다른 동형 연산의 입력으로 사용이 가능한 성질
  보안성 - 암호환된 형태로 연산이 진행되어 해킹 차단이 가능한 성질
상세설명
  E(m1) + E(m2) = E(m1 + m2) - 평문에 연산을 하여 암호화한 것과 평문을 암호화한 후 연산을 한것은 서로 같다
  E(m1) * E(m2) = E(m1 * m2) -  상수곱, XOR, AND등 모든 논리 연산 보존이 가능하다
유형 부준완
  부분 동형암호 (Partially Homomorphic Encryption, PHE)
    - 주어진 데이터 셋에 대해 한 가지 유형의 수학 연산만 허용
  준 동형암호 (Somewhat Homomorphic Encryption, SHE)
    - 주어진 데이터 집합에 대해 덧셈과 곱셈을 몇 차례만 허용
  완전 동형암호 (Fully Homomorphic Encryption, FHE)
    - 데이터에 대해 횟수에 제한없이 다양한 유형의 연산을 허용 
알고리즘 RGB 7895
  RAD 78 - 최초의 동형암호, 느리고 용량큼
  GEN 09 - 격자기반, 난수화된 에러 사용
  BGN 05 - 덧셈과 한번의 곱셈연산 보존
설계원리 부비 스복공
  부트스트래핑 - 암호문에 암호화된 비밀키를 이용하여 노이즈 감소된 새로운 암호문 생성
  스쿼싱 - 복호화 알고리즘과 공개키를 일부 변형하여 미리 필요한 연산을 수행

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
