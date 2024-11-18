---
title: 스레싱
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 운영체제]
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
      I. 페이지 교체의 역기능, 쓰레싱
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 스레싱의 정의
        </div>
        <div class="para-cntnt">
            멀티프로세싱 환경 페이지부재가 자주 일어나 프로세싱보다 교체시간이 더 많아지는 현상
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 스레싱
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 스레싱의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/스레싱.png" alt="스레싱">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 스레싱의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            상세) 멀티 프로세싱 환경에서 가상메모리의 페이지 부재
원인 멀리교
  멀티프로그래밍
    멀티프로세스 - 과도한 멀티 프로그래밍으로 잦은 페이지 부재 발생
    페이지부재 - 수용 가능한 페이지수 초과에 따른 잦은 페이지 부재 발생
  리소스부족
    저사양 CPU - CPU의 Core 개수 및 속도 리소스 부족
    메모리 부족 - 메모리 용량 부족으로 인한 가상메모리 사용 증가
  페이지 교체정책
    Locality - 미고려 인한 페이지 교체 정책의 효율성 저하
    Belady's Anomaly - 페이지 프레임 수를 늘리면 특정 패턴에 대해 페이지 폴트 수가 증가 
해결방안 PFF, WSM
  멀티프로그래밍
    멀티스레딩 사용 - 여러 작업을 동시에 수행함으로써 쓰레싱을 완화
    우선순위 조절 - 동적으로 우선순위를 조절하여 메모리를 할당
  리소스부족
    메모리 할당 - 메모리 용량을 늘리거나 프로세스들에게 적절한 메모리를 할당
    스와핑 조절 - 메모리에 있는 데이터를 디스크로 옮기는 작업
  페이지 교체정책
    Working Set Model - Locality 표현 Working set 을 메모리에 상주하게 하고 모니터링, Frame 할당 조정하여 스레싱 최소화 기법
    기술요소
      Reference Page - 프로세스가 참조하는 주기억 장치의 페이지
      WSS(Working Set Size) - 특정시간 동안 메모리 상에 참조된 페이지 수
      Working Set Windows Size - Working Set의 고정된 참조 페이지 크기
    Page Fault Frequency - 페이지 부재율의 상한과 하한을 기반으로 할당, 회수하여 조절하는 기법
    기술요소
      상한선 (Upper Bound) : 프로세스 페이지 프레임을 추가 할당하여 적정범위 유지
      하한선 (Lower Bound) : 프로세스 페이지 프레임을 회수하여 적정범위 유지
효과적 페이징 고려사항 프인지입
  Pre-paging - 모든페이지 한꺼번에 로드
  Inverted Page Table - 메모리 공간 줄이는 기법
  지역성 고려 - 프로그램 개발시 언어에 따른 지역성 고려
  입출력 잠금 - 사용자공간으로는 IO 방지
- 스레싱을 근본적으로 줄이기 위해 다중 프로그래밍 정도를 낮추어야 함(데닝은 50% 정도를 제안)

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
