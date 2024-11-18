---
title: 매니코어 프로세서
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
      I. 집적코어 프로세서, 매니코어 프로세서
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 매니코어 프로세서의 정의
        </div>
        <div class="para-cntnt">
            속도향상을 위해 프로세서에 다수코어 집적하여 NoC 통해 코어간 속도향상 고성능 프로세서
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 매니코어 프로세서
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 매니코어 프로세서의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/매니코어-프로세서.png" alt="매니코어 프로세서">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 매니코어 프로세서의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          기술요소 노누디 컨하소
  프로세싱 
    NoC - 프로세서 내부통신 속도 향상 (NoC = Network on Chip)
    NUCA -  지리적 가까운 L2 캐시 이용 (Non Uniform Cache Architecture)
    DVFS - 연산량에 따라 동적 전압, 주파수 조절 (Dynamic Voltage Frequency Scaling)
  메모리
    Controller - 프로세서 내부 L3 캐쉬대신 MC 집적, 메모리 접근속도 향상
    HBM - 고대역폭 메모리 사용
    STM - 메모리 동시성 제어기법 (Software Transactional Memory)
매니코어와 멀티코어 비교
  코어수 : 수백개 코어 &lt;&gt; 수십 코어
  메모리 : 분산메모리 &lt;&gt; 공유메모리
  프로그래밍 : 고난이도 동기화 &lt;&gt; 단순 멀티프로그래밍 
  활용 : AI, 로보틱스 &lt;&gt; pc, 노트북 

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
