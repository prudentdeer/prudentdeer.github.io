---
title: DiffServ
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
      I. 차등 서비스모델, DiffServ
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DiffServ의 정의
        </div>
        <div class="para-cntnt">
            IntServ 모델 한계극복 위해 클래스단위로 서비스 가중치 차별화하여 QoS를 보장하는 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. DiffServ
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. DiffServ의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/DiffServ.png" alt="DiffServ">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. DiffServ의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 분마컨큐
  분류자 (Classifier) - 해당 패킷을 클래스 별로 구분하는 단계로 ACL와 Class-Map을 통하여 구별
  마킹 (Marking) - 구분한 클래스에 대해 Policy-Map을 통해 마킹을 하여 우선순위를 지정
  컨디셔너 (Conditioner) - 버퍼를 이용하여 조절하는 Shaping과 Drop을 이용한 Policing 두 가지 방법
  큐잉 (Queuing) - 큐잉 기법으로 FIFO, WFQ, CQ, PQ, CBWFQ, LLQ 등
IntServ 와 DiffServ 비교
  특성 : 절대적 보장을 지원하는 QoS방식 &lt;&gt; Backbone망에서도 확장성을 지원하는 QoS방식
  QoS보장 흐름(flow)별 보장, 절대적 서비스 품질제공 &lt;&gt; 그룹별(Class of Service), 상대적 서비스 품질
  보장범위 : 단대단 &lt;&gt; 도메인(Edge-to-Edge)
  장점 : 엄격한 QoS보장이 가능, 실시간 어플리케이션 지원가능 &lt;&gt; 구축을 위한 투자비용이 낮음, 구성의 복잡도가 낮음, 높은 확장성
  단점 : 경로상의 모든 라우터가 Flow 상태 관리, 트래픽이 집중하는 Core망 에서 부적절함 &lt;&gt; 종단간에 서비스 품질을 보장할 수 없음, 실시간 어플리케이션 지원이 어려움

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
