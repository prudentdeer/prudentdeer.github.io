---
title: QoS
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
      I. 네트워크 서비스 품질 향상을 위한 기술, QoS의 개요
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. QoS의 정의
        </div>
        <div class="para-cntnt">
            종단간 서비스 품질과 성능을 일정수준 보장하여 사용자 요구를 충족 시키는 네트워크 기술 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. QoS
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. QoS의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/QoS.png" alt="QoS">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. QoS의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          측정지표 유타카투 대지터패신가
  대역폭 / Shapping, Policing - 일정시간에 처리한 데이터의 총량을 가리키는 지표 (Bandwidth)
  지연 / MPLS, CDN - 발생지에서 목적지까지 가는 경로에서 발생되는 지연 (Delay) 
  지터 / 전용선, 신뢰경로 - 원래 신호로부터 왜곡되는 정도 (Jitter) 
  패킷손실 / 혼잡회피, IPv6 - 데이터를 전송하는 과정에서 패킷의 손실 정도 (Packet Loss)
  신뢰성 / 흐름제어, 에러제어 - 전송되는 신호가 오류, 왜곡 등에 덜 취약하도록 하는 기술
  가용성 / HA, 로드밸런싱 - 요구기능을 요구시간동안 올바르게 수행가능 능력
QoS와 QoE 비교
  개념 – 제공하는 서비스의 품질 &lt;&gt; 사용자가 경험, 인지하는 품질
  목적 - 일관된 수준 성능유지 &lt;&gt; 만족도 최대화, 사용자 경험 향상
  주요지표 – Packet Jitter, Packet Loss &lt;&gt; 선명한 화질, 끊김 없음
  특징 - 이용계약에 대한 근거자료 &lt;&gt; 품질이 낮더라도 저비용이 QOE가 높을 수 있음

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
