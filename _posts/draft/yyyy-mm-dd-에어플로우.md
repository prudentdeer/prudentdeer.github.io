---
title: 에어플로우
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
      I. 데이터 파이프라인을 위한, Airflow
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 에어플로우의 정의
        </div>
        <div class="para-cntnt">
            파이썬 코드이용 프로그래밍 방식으로 워크플로우를 작성, 스케쥴링, 모니터링하는 오픈소스 플랫폼
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 에어플로우
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 에어플로우의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/에어플로우.png" alt="에어플로우">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 에어플로우의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  Webserver - 스케줄러에서 분석한 Dag 시각화
  Schedular - DAG를 분석하고 DAG의 태스크를 예약
  Worker - 예약된 태스크를 실제로 실행시키는 것
  Metastore - 에어플로우에 있는 Dag, Task등의 메타데이터 관리
  Executor : 태스크가 어떻게 실행되는지 정의
  DAG - task들 간의 관계와 dependency를 표현
Airflow Operator 
  BashOperator - bash command를 실행 
  PythonOperator - python 함수를 실행
  MysqlOperator - sql 쿼리를 수행
  Sensor - 시간,파일, db row 등을 기다리는 센서

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
