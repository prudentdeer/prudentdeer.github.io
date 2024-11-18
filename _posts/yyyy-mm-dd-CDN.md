---
title: CDN
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
      I. 위치/캐시기반 빠른 컨텐츠 서비스, CDN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CDN의 정의
        </div>
        <div class="para-cntnt">
            대용량의 컨텐츠를 미리 옮겨놓고, 캐싱 및 가속기술 통해 컨텐츠를 빠르게 전달하는 캐싱기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. CDN
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CDN의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/CDN.png" alt="CDN">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. CDN의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          기술요소 캐로글스
  Cashing - 자주 찾는 페이지를 컴퓨터에 복사해 저장
  Loadbalancing - 서버별 트래픽 분산
  GLB - 최상서비스 캐시서버 선정
  SLB - 서버 부하분산 로드밸런싱
컨텐츠 전송방식 푸캐스
  푸싱 - 서버의 컨텐츠를 캐시서버로 전송
  캐싱 - 사용자 요청 컨텐츠를 캐시서버가 제공
  스플리팅 - 하나의 스트림으로 컨텐츠 받은후, 스트리밍으로 사용자 전송
CDN, ADN 비교
  목적 - 느린응답 해결 &lt;&gt; 트래픽 속도증가
  기능 - 캐싱, 로드 밸런싱 &lt;&gt; 가속화, 트래픽 관리
  캐싱 - 정적 &lt;&gt; 동적
- CDN은 "캐싱(Caching) 기술"이고 ADN은 "가속(Acceleration) 기술"

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
