---
title: Traffic Shaping
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
      I. 버퍼를 이용한 QoS 보장, Traffic Shaping 개요
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Traffic Shaping의 정의
        </div>
        <div class="para-cntnt">
            네트워크 혼잡회피 위해 유입, 유출 트래픽 양과 속도를 버퍼를 통해 조절하는 QoS 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Traffic Shaping
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Traffic Shaping의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Traffic-Shaping.png" alt="Traffic Shaping">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Traffic Shaping의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  CBS : 허용 버스트 크기 - 정해진 시간동안 네트워크 전송가능 최대 비트 수 (Committed Burst Size)   
  CIR : 허용 정보율 - CIR = BC / T bps (Committed Information Rate)   
  EBS : 초과 버스트 크기 - 정의된 기간 동안 CBS 초과 전송가능 최대 비트 수 (Excess Burst Size)
알고리즘 쉐토리하
  Token Bucket (속도제어) : 하나의 셀이 하나의 토큰 사용, 흐름이 부드럽게 유지
  Leaky Bucket (용량제어) : 항상 정해진 일정량 만 나오도록 함, 트래픽 버킷에 저장, 버킷 과도 시 폐기 
  Hybrid Bucket (속도용량)

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
