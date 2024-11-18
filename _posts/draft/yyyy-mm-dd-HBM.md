---
title: HBM
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
      I. 주상복합형 반도체, HBM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. HBM의 정의
        </div>
        <div class="para-cntnt">
            고성능 데이터 처리를 위해 DRAM 적층, TSV, SoC 기반 병렬처리 지원 고대역폭 메모리
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. HBM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. HBM의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/HBM.png" alt="HBM">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. HBM의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  적층화 티디로마 소피실패
    TSV - DRAM Die를 뚫어 전도성 재료를 채운 수직 실리콘 관통 전극, Through Silicon Via
    DRAM Die - DRAM Cell 그룹, 패키징 단위
    Logic Die - 다른 칩셋 및 PHY와 DRAM die 연결
    Micro Bump - 미세 돌기모양 금속으로 반도체 간 접합 연결
  칩셋구성
    SoC - System on Chip, 그래픽 및 명령어 처리 프로세서
    PHY - Base die와 Process die 간 연결하는 물리 계층 인터페이스
    Silicon Interposer - 다수 범프 수용을 위해 패드/금속 배선으로 HBM, Logic Chip 연결
    Package substrate - HBM, SoC, CPU, GPU 칩 등을 연결하는 PCB 기판
HBM의 활용분야
  AI
    온디바이스 AI
    AIoT
  CA
    뉴로모픽칩
    GPU
HBM3 와 GDDR6 비교
  용도 - AI 학습용 &lt;&gt; 그래픽 카드
  Bandwidth - 819 GB/s &lt;&gt; 64 GB/s
  Pin - 1,024개 &lt;&gt; 32개
  Pin Data Rate - 6.4 Gbps &lt;&gt; 16 Gbps

- 발열, 패키징 한계 극복위해 하이브리드 본딩기술 개발중
- 하이브리드본딩 - 적층하는 반도체(다이)를 구리로 직접 연결(Cu to Cu)하는 기술
  칩 사이의 간격을 줄여 신호 전달 속도를 높이고 메모리 성능을 극대화

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
