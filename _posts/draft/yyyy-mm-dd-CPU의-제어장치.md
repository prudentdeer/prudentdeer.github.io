---
title: CPU의 제어장치
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
      I. CPU 내부 자원 제어의 핵심, 제어장치
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CPU의 제어장치의 정의
        </div>
        <div class="para-cntnt">
            메모리에서 명령어를 읽어 해석하여 제어신호를 자원에 전달하고 동작을 명령하는 CPU의 장치 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. CPU의 제어장치
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CPU의 제어장치의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/CPU의-제어장치.png" alt="CPU의 제어장치">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. CPU의 제어장치의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          역할
  데이터 저장 - 입력 장치에서 입력된 데이터를 기억장소에 저장
  연산장치 전달 - 기억 장치에 있는 데이터를 연산장치로 이동
  기억장치 전달 - 연산 장치에서 연산이 완료되면 그 결과를 기억장치로 이동
  데이터 출력 - 기억 장치에 저장된 데이터를 출력장치로 이동시켜 출력
구성요소 해주기버해
  명령어해독기 - 명령어와 연산코드를 해독하여 연산을 수행하기 위한 루틴의 시작주소 결정
  주소레지스터 - 다음에 실행할 마이크로 명령어의 주소를 저장하는 레지스터
  기억장치 -  마이크로 명령어들로 이루어진 마이크로 프로그램을 저장
  버퍼레지스터 - 제어 기억장치로부터 읽힌 마이크로 명령어
  해석기 - 서브루틴 레지스터, 순서제어모듈로 구성
구현유형
  고정제어 / RISC - 조합회로 이용하여 하드웨어로 구현
  마이크로프로그래밍 제어 / CISC - 제어신호 조합을 프로그램으로 저장

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
