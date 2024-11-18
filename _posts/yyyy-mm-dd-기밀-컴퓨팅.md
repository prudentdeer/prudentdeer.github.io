---
title: 기밀 컴퓨팅
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
      I. 기밀 컴퓨팅
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 기밀 컴퓨팅의 정의
        </div>
        <div class="para-cntnt">
            사용중인 데이터 보호하고 코드무결성 보장위해 TEE, 가상머신 단위, 위변조 확인 기반의 컴퓨팅
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 기밀 컴퓨팅
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 기밀 컴퓨팅의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/기밀-컴퓨팅.png" alt="기밀 컴퓨팅">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 기밀 컴퓨팅의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            메모리에 적재되어 사용 중인 데이터 보호 위해 TEE에서 계산을 수행하여 하드웨어 기반으로 데이터를 보호하는 기술
활용기술
  TEE
    Intel SGX - 엔클레이브(enclave)라고 하는 보호 영역을 설정해 CPU가 메모리 일부를 암호화
    ARM TrustZone - 하드웨어에서 직접 실행되며 하나의 CPU를 일반구역과 보안 구역 분할 관리
  암호화
    완전동형암호 – 암호문을 AND, XOR 연산을 통해 복호화 없이 수행
    SMPC – 영지식 증명, 차분 프라이버시, 합성 데이터, 연합 학습
  응용프로그램 기반 
    실행증명 - 기존 코드의 위변조 여부 확인 가능 기술 
    Root of Trust  - 시스템의 어떤 부분을 신뢰할 수 있다고 가정하고 그 위에 보안 기능 구현 기술 
    가상머신단위 구현 - 가상머신단위 신뢰할 수 있는 프로그래밍 모델 구현

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
