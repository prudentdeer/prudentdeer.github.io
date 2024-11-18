---
title: RAN Sharing
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 네트워크]
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
      I. 공공안전망 구현, RAN-Sharing
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. RAN Sharing의 정의
        </div>
        <div class="para-cntnt">
            공공안전망 구축위해 700mhz 대역 간섭없는 MORAN, MOCN, GWCN 기반 무선 공유기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. RAN Sharing
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. RAN Sharing의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/RAN-Sharing.png" alt="RAN Sharing">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. RAN Sharing의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          목적 전할비연
  전파간섭 문제 - PS-LTE, LTE-R, LTE-M 모두 700mhz 사용
  할당대역 협소 - 재난안전용 대역은 20mhz에 불과
  비용절감 - 기지국 공유로 인해 운영, 구축비 절감
  연속성확보 - 재난대응 간 상호통신 연속성 확보
유형 / 공유 / 특징 서코컨기주
  MORAN / 컨트롤러, 기지국 - 가장 작은 단위만을 공유하는 방식 (Multi Operator RAN)
    - 컨트롤러, 기지국만을 공유하고 코어망과 주파수는 별도로 구축하는 Ransharing 기술
  MOCN / 컨트롤러, 기지국, 주파수 - 스펙트럼 공유방식, eNB, gNB 공유방식 (Multi Operator Core Network)
    - 컨트롤러, 기지국, 주파수 공유하고 코어망을 별도로 구축하는 Ransharing 기술
  GWCN / 컨트롤러, 기지국, 주파수, 코어 - 코어망 S-GW 공유, P-GW 분리설정 (GateWay Core Network)
    - 컨트롤러, 기지국, 주파수, 코어 공유하고 S-GW 공유, P-GW 분리 Ransharing 기술
비교
  MORAN &lt;&gt; MOCN &lt;&gt; GWCN
  개념 - 주파수, 코어망 별도구성 &lt;&gt; 코어망만 별도구성 &lt;&gt; GW만 분리
  확장성 - 높음 &lt;&gt; 보통 &lt;&gt; 낮음
  장점 - 차별화 가능 &lt;&gt; 구현, 비용 유리 &lt;&gt; 비용 유리
  단점 - 구현, 비용 불리 &lt;&gt; 차별화 없음 &lt;&gt; 구현 불리
&gt;&gt; 간섭 최소화와 중복구축 영향 줄이며 연속성 확보
* eNB : 4g 기지국 / gNB : 5g 기지국

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
