---
title: 하드웨어 규모산정
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 필수암기]
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
      I. 133
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 하드웨어 규모산정의 정의
        </div>
        <div class="para-cntnt">
          정의
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 하드웨어 규모산정
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 하드웨어 규모산정의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/하드웨어-규모산정.png" alt="하드웨어 규모산정">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 하드웨어 규모산정의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            정보시스템 기본적 용량과 성능요구 제시시 하드웨어 요구사항으로 변환하는 산정기법
절차별 활동 구기참가
  구축방향, 기초자료 조사 / ISP, 아키텍처 수립 - ISP, 기본계획 토대로 전체 아키텍처 모델 수립, 자료수집
  기초자료, 업무분석 / 기준부하 산정 - 1단계 바탕으로 업무분석, 예상부하 결정, 합산하여 기준부하 산정
  참조모델 결정, 서버 규모산정 / 보정치 결정 - 참조모델과 보정치 결정, 구성요소 규모산정
  참조모델별 가중치 적용 / 가중치 적용 - 아키텍처에 따라 모델별 가중치로 규모확정
방법 수참시
  수식계산법 - 산정요소 (사용자 수 등) 토대로 용량수치 계산 후 보정치 적용
    근거 명확제시, 간단하게 산정 / 보정치가 잘못되었을 경우 많은 차이가 발생
  참조법 - 업무량, 기존 데이터 토대 산정
    안전한 규모 산정, 신뢰성이 높음 / 근거를 명확히 제시하기 어려움
  시뮬레이션법 - 작업부하를 모델링 규모 산정
    정확한 산정결과 / 많은 시간과 비용이 소요
대상 씨메디 시데스
  서버
    CPU - 업무처리위한 CPU 규모 계산
    메모리 - 시스템, 응용프로그램 등 메모리 사용량
    디스크 - 시스템, 데이터베이스
  스토리지 - CPU 기준 산정규모에 따라 필요한 스토리지 산정
참조모델별 가중치
  참조모델 1 - 단일 서버, CPU 규모 상대가중치 2.1
  참조모델 2 - WEB/응용서버 2개 서버, 1.6, 응용/DB서버 1.7
  참조모델 3 - 3개 서버, 가중치 미적용

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
