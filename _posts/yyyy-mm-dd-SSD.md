---
title: SSD
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 컴퓨터구조]
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
      I. NAND-FLASH기반의 차세대 보조 기억장치, SSD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SSD의 정의
        </div>
        <div class="para-cntnt">
            NAND 플래시를 이용하여 고속, 저지연, 저전력의 특징을 갖는 HDD 대체하는 보조기억장치
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SSD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SSD의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SSD.png" alt="SSD">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SSD의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 컨플디케
  제어
    Controller - Memory Block의 여러 개 채널 관리
  저장
    FlashMemory - 패키지 수준의 다중 칩 적층 기술 적용
    DRAM - 읽기/쓰기 요구속도 최적화를 위한 데이터 캐시 및 버퍼
  전원공급    
    Capacitor - DRAM과 같은 휘발성 메모리, 정전에 대비
핵심기술 웨가오플
  Wear Leveling - 컨트롤러가 각 블록의 삭제횟수를 기억, 가장 낮은 삭제횟수 블록에 기록
  Garbage Collection - 블록을 삭제하지 않고, Garbage 표기 후(X) 일괄 삭제하는 기술
  Over Provisioning - 여유공간 부족시 문제점 극복 위한 여유공간  
  FTL - 블록/페이지 기반의 SSD를 섹터기반 HDD처럼 인식 (FlashTransaction Layer)
SSD 와 HDD 비교
  구성요소 - Block / Page 단위 &lt;&gt; Track / Sector
  처리속도 - 초당 수백 MB &lt;&gt; 초당 수십 MB
  저장소자 - NAND 플래시 &lt;&gt; 플래터
  작동방식 - 전기적 신호 &lt;&gt; 헤드 암의 기계방식
  장점 - 저지연, 충격에강함 &lt;&gt; 비용저렴, 긴 수명
  단점 - 고가, 짧은 수명 &lt;&gt; 충격에약함, 무거움, 고전력, 소음
- 쓰기속도 저하 이슈 Write-Cliff 해결 Wearleveling, GC, OP

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
