---
title: Traffic Policing
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
      I. 트래픽 대역폭 제한을 통한 QoS 보장, Traffic Policing 개요
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Traffic Policing의 정의
        </div>
        <div class="para-cntnt">
            네트워크 혼잡회피 위해 미리 정의된 기준초과 트래픽 DROP, 대역폭 제한하는 QoS 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Traffic Policing
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Traffic Policing의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Traffic-Policing.png" alt="Traffic Policing">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Traffic Policing의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  Meter : 수신되는 패킷의 유입률(bps) 측정  
  Drop : 유입률이 약속된 대역폭 이상이면 패킷을 Drop   
  Mark : 유입률이 약속된 대역폭 이하이면, 해당 패킷에 Marking 한후 포워딩
알고리즘 폴레가테
  RED - 혼잡사항 사전감지 Drop (Random Early Detection)
  WRED - 패킷 가중치에 따라 Drop (Weighted Random Early Detection)
  Tail Drop - 버퍼 임계치 초과시 모두 Drop

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
