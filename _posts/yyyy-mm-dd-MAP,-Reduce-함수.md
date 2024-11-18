---
title: MAP, Reduce 함수
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 데이터베이스]
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
      I. HDFS 기반 대용량 데이터 분석 프레임워크, Map Reduce의 개요
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MAP, Reduce 함수의 정의
        </div>
        <div class="para-cntnt">
            HDFS 대용량 데이터를 분석하기 위한 분석 환경에서의 병렬처리를 지원하는 프레임워크
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MAP, Reduce 함수
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MAP, Reduce 함수의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MAP,-Reduce-함수.png" alt="MAP, Reduce 함수">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MAP, Reduce 함수의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          개념
  Map : 흩어져 있는 데이터를 Key, Value의 형태로 연관성 있는 데이터 분류로 묶는 작업
  Reduce : Map화 한 작업 중 중복 데이터를 제거하고 원하는 데이터를 추출하는 단계
프로세스 인스매셔리파
  Input
  Split - 입력 데이터를 Split 단위로 분할
  Map - Split를 하나씩 읽어 Key, Value 세트로 저장
  Shuffle - Reduce에서 처리 가능하도록 병합 및 정렬
  Reduce - 정렬이 끝난 데이터는 (Key, Value)로 통합
  Final Result - HDFS에 저장

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
