---
title: IVN
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
      I. 차량의 내부 네트워크, IVN 의 개요
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IVN의 정의
        </div>
        <div class="para-cntnt">
            차량 내부에서 CAN, LIN, MOST 통해 개인편의, 차량안전을 지원하는 차내 유선 네트워크
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IVN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IVN의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IVN.png" alt="IVN">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IVN의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형
  CAN - 차량내부 ECU와 장치간 통신 (Control Area Network)
  LIN - 분산된 전자시스템을 위한 저비용의 직렬 통신 (Local Interconnect Network)
  MOST - 멀티미디어 정보를 전송하는 시리얼 통신 (Media Oriented System Transport)
  FlexRay - 대역폭 부족 해결위해 개발된 제어 네트워크
LIN 특징
  Single Master 통신구조 : 모든통신은 Master 노드에서 시작하며 Slave 노드는 Master 노드가 내리는 명령에 응답
  버스형 토폴로지 : 하나의 Master에 최대 15 노드까지 Slave 노드를 접속가능
  통신속도 : 1~20 Kbps 범위 내 통신속도 사용
  에러검출 : 애플리케이션에 맞추어 에러 처리를 임의로 설계
MOST 특징
  링형 토폴로지 : 최대 64개 장치로 구성가능
  플러그앤플레이 : 장치의 추가 및 제거가 용이
  높은 QOS : 전용 채널을 예약, 스트리밍 제공
CAN, LIN, MOST, Flexray 비교
  특징 - 실시간 &lt;&gt; 저속 &lt;&gt; 멀티미디어 &lt;&gt; 고성능
  제어 - 멀티마스터 &lt;&gt; 싱글마스터 &lt;&gt; 타이밍마스터 &lt;&gt; 멀티마스터
  통신 - TwistedPair &lt;&gt; 단선 &lt;&gt; 광통신 &lt;&gt; TwistedPair
- SDV시대 대비 CAN에서 Ethernet으로 전환진행중

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
