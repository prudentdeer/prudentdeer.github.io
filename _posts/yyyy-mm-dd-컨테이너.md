---
title: 컨테이너
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
      I. 커널은 공유 환경은 격리, 컨테이너
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 컨테이너의 정의
        </div>
        <div class="para-cntnt">
            LXC 기반 커널공유 프로세스간 Cgroup, Namespace, Libvert 이용 격리환경 가상화 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 컨테이너
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 컨테이너의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/컨테이너.png" alt="컨테이너">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 컨테이너의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  Hypervisor 없이 가상화, Cgroup 이용 자원 분할 할당, Namespace 분리, 컨테이너 간 접근 분리
기술요소 SCSC PMNI
  Cgroups - 프로세스 그룹 자원제한, 격리, 모니터링
    Subsystem - Cgroup에서 제어 가능한 시스템 자원
    Cgourp FS - 커널에서 제공하는 cgroup 인터페이스
    Sub-sys Class - Subsystem file 값 변경 시, 이를 인지하여 kernel 함수 호출
    Cgroup Kernel - Cgroup 기반스케줄링,시스템자원등제어
  Namespace - 운영환경 고립, 독립공간 제공
    Pid - 프로세스 실행공간 분리
    Mnt - 독립적 파일시스템 마운트 가능
    Net - namespace 간 네트워크 충돌방지
    Ipc - 프로세스 간 독립적 통신 통로 할당
가상 머신 (VM), 컨테이너 비교
  가상화 - 하드웨어 수준 &lt;&gt; 운영체제 수준
  격리 - 운영체제 수준 &lt;&gt; 프로세스 수준
  성능 - 무겁고 느림 &lt;&gt; 가볍고 빠름
  호환성 - 다양한 OS &lt;&gt; 호스트와 같은 OS
- MSA 환경구축시 vm / 컨테이너 최적화

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
