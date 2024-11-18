---
title: 메모리 인터리빙
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
      I. 효율적인 메모리 접근, 메모리 인터리빙
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 메모리 인터리빙의 정의
        </div>
        <div class="para-cntnt">
            메모리 접근시간 최소화를 위해 모듈로 분할, 주소부여하고 병렬접근하는 성능향상 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 메모리 인터리빙
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 메모리 인터리빙의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/메모리-인터리빙.png" alt="메모리 인터리빙">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 메모리 인터리빙의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          인터리빙 활용방식 상하혼뱅모
  상위인터리빙 - 1개의 메모리 모듈내에 모듈의 주소지정 범위 만큼의 주소가 연속적으로 저장
    한 모듈 에러시 해당 모듈만 영향을 받음 / 동시 액서스를 통한 성능 향상이 어려움
    - 상위 비트 MSB - 모듈 선택 신호로 사용 &lt;디코더&gt;
    - 하위 비트 LSB - 모듈 내 기억장소 선택
  하위인터리빙 - 모듈단위로 기억장치주소가 순차 부여
    다수의 모듈이 동시 동작 (액서스 향상) / 한 모듈의 에러가 전체에 영향
    - 상위 비트 MSB - 모듈 내 기억장소 선택
    - 하위 비트 LSB - 모듈 선택 신호로 사용 &lt;디코더&gt;
  혼합인터리빙 - 기억장치 모듈을 뱅크로 그룹화
    하위 인터리빙의 단점인 결합 허용도와 상위 인터리빙 단점인 동시 액서스 극복
    - 그룹(뱅크) 선택 - 상위 인터리빙 활용 &lt;디코더&gt;
    - 그룹(뱅크)내 모듈 - 하위 인터리빙 활용 &lt;디코더&gt;
- 버스의 경합이나 기억장치의 충돌 회피
메모리 엑세스 방식 CS
  C-엑세스 / 순차접근, 상위인터리빙 - 주소들이 순차적으로 기억장치 모듈에 도착 (Concurrent-access) 
  S-엑세스 / 병렬접근, 하위인터리빙 - 모든 기억장치 모듈에서 동작이 동시에 시작, 데이터 순차적으로 전송 (Simultaneous-access)
- 캐시나 빠른 데이터 전송을 위한 DMA(Direct Memory Access)에서 많이 사용

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
