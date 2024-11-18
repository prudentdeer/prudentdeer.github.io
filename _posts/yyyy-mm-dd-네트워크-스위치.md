---
title: 네트워크 스위치
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
      I. 유니캐스트, 네트워크 스위치
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 네트워크 스위치의 정의
        </div>
        <div class="para-cntnt">
            네트워크 장치간 상호연결 위해 Full-duplex, 패킷스위칭, MAC 주소 기반 데이터 전송 장비
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 네트워크 스위치
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 네트워크 스위치의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/네트워크-스위치.png" alt="네트워크 스위치">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 네트워크 스위치의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  동작측면
    MAC주소 사용 - MAC 주소 기반한 라우팅 기능
    Full Duplex - 전이중 통신방식 지원, 수신과 송신 동시에
  성능측면
    전송속도 개선 - 허브보다 전송속도 개선
    병목현상 감소 - 필요한 곳에만 데이터 전송하여 병목 감소
스위치의 유형
  L7 Layer / L7 스위치 - 컨텐츠기반 로드밸런싱, 패킷 분석, 네트워크 보안, 트래픽 차단
  L4 Layer / L4 스위치 - 포트기반 로드밸런싱, 부하분산, 그룹화
  L3 Layer / L3 스위치 - 라우팅, VPN, VLAN 지원
  L2 Layer / L2 스위치 - MAC 주소기반 포워딩, Filtering, Flooding
L4 스위치와 L7 스위치의 비교 (둘다 로드밸런싱 하는데, 차이가 있음)
  개념 - 4계층 포트기반 트래픽제어 &lt;&gt; 7계층 기반 트래픽 제어
  목적 - 포트 로드밸런싱, HA 지원 &lt;&gt; 컨텐츠 로드밸런싱, HA 지원
  특징 - 필터링, 미러링 &lt;&gt; L4기능 + 컨텐츠기반 제어
  보안 - L2~L4 기반 보안기능 &lt;&gt; 컨텐츠 기반 안티바이러스
  장점 - 빠른속도, L7 대비 저비용 &lt;&gt; 헤더값에 따른 로드밸런싱 가능
  단점 - 서비스 유무만 확인가능 &lt;&gt; L4대비 고비용, 성능저하
  활용 - WAS 이중화 &lt;&gt; 웹방화벽

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
