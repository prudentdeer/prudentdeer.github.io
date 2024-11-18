---
title: SNN
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
      I. 뉴로모픽 칩 알고리즘, SNN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SNN의 정의
        </div>
        <div class="para-cntnt">
            뇌를 구성하는 뉴런과 시냅스로 이루어진 신경망 구성 방식으로 구현하는 저전력 인공신경망
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SNN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SNN의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SNN.png" alt="SNN">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SNN의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          동작기술 스시가 뉴막스
  Input
    InputSpike - 스파이크 입력 전송
    Synapse - 수상돌기(dendrit) 역할을 하는 Spiking 전송
    Weight - 시냅스의 가중치를 곱하여 뉴런 전달
  Output
    Neuron - 문턱전압 (threshold voltage)을 넘게 되면 출력으로 전달
    막전위 - membrane potential
    OutputSpike - 축삭돌기(axon) 역할을 하는 Spiking 전송
SNN 과 DNN 비교
  구현원리 - 뇌의 생물학 특성 모방 &lt;&gt; 뇌가 패턴을 인식하는 방식 모방
  동작특성 - 이벤트기반, 저전력 &lt;&gt; 연속적 데이터 모델링, 고전력
  학습형태 - 신경세포 &lt;&gt; 전체 학습
  하드웨어 - 뉴로모픽 칩 &lt;&gt; GPU
- STDP 시냅스가중치 조절 알고리즘

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
