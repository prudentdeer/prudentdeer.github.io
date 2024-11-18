---
title: Fingerprint 기법
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 디지털서비스]
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
      I. &lt;네트워크 기반 무선 측위 방식, fingerprint 방식의 개요&gt;
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Fingerprint 기법의 정의
        </div>
        <div class="para-cntnt">
            서비스 지역의 위치좌표와 전파환경을 미리 DB로 구축한 후 단말기에서 올라온 전파특성을 해당 DB와 매칭하여 위치를 결정하는 LBS 무선측위방식
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Fingerprint 기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Fingerprint 기법의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Fingerprint-기법.png" alt="Fingerprint 기법">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Fingerprint 기법의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  확률론적 모델링에 의한 위치 추정방식
  주위의 환경 상황이 반영되므로 정확한 측위가 가능
  무선랜 기반의 측위 시스템에서 가장 많이 사용되는 위치측위 방식
&lt;개념도&gt; 와 상세설명
  Training 단계
    - 위치 측위 대상이 되는 공간을 일정한 범위로 구획
    - 각 측위 지점(P:Point)의 위치 값을 데이터베이스에 저장
    - 위치 값과 함께 액세스포인트로부터 단말기에 도달한 신호 세기를 측정하여 추출한 전파 특성값을 저장
    - 이 과정은 측위 대상이 되는 공간의 모든 측위 지점을 측정할 때까지 반복적으로 수행
  Positioning 단계
    - 단말기를 가진 사용자가 위치를 요청
    - 단말기의 위치를 요구하는 장소에서 신호 세기를 측정한 후 데이터를 서버로 전송
    - 데이터를 전송 받은 위치 측위 서버는 측정된 신호와 저장된 데이터베이스의 신호를 비교
    - 요구한 단말기의 위치와 가장 적합한 위치 데이터 정보를 결정한 후 위치값을 단말기에게 제공

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
