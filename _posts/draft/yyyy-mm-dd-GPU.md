---
title: GPU
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
      I. GPU
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. GPU의 정의
        </div>
        <div class="para-cntnt">
            그래픽 처리 특화, 병렬처리 기반의 수백개의 ALU, CUDA 로 구성된 그래픽 프로세서
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. GPU
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. GPU의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/GPU.png" alt="GPU">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. GPU의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          등장배경
  그래픽처리 증가 - GUI와 응용 프로그램
  게임산업 성장 - 빠른 렌더링과 고해상도 그래픽 필요
  병렬처리 필요 - 스레드로 처리위해 병렬 아키텍처 필요
  아키텍처의 발전 - CUDA와 OpenCL 프로그래밍 모델
GPU와 CPU 차이점
  용도 - 그래픽 및 병렬 계산 &lt;&gt; 일반 계산
  주요기능 - 병렬 처리  &lt;&gt; 단일 스레드 작업
  핵심설계 - CUDA 코어, 스트림 프로세서  &lt;&gt; 캐시, 파이프라인, 제어 유닛, ALU 등
  연산유닛 - 수백개 코어 &lt;&gt; 수십개 코어
  클럭속도 - MHz 단위 &lt;&gt; GHz 단위
  스레딩 - 수천 개의 스레드 &lt;&gt; 몇 개의 스레드
  메모리계층 - 다수 레벨 &lt;&gt; 소수 레벨
  에너지효율 - 낮은 에너지 효율성 &lt;&gt; 높은 에너지 효율성
  소비전력 - 고전력소비 &lt;&gt; 중간전력소비
  효율성 - 병렬 작업 및 그래픽 연산 &lt;&gt; 단일 스레드 작업
  사용사례 - 렌더링, 딥 러닝, 암호화, 채굴 &lt;&gt; 서버, 데스크톱, 노트북

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
