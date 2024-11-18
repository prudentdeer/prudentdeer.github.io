---
title: 오류제어
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 네트워크]
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
      I. 오류제어
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 오류제어의 정의
        </div>
        <div class="para-cntnt">
            네트워크상의 정보 전달 과정에서 발생하는 전송중단, 혼선 등의 예외상황 처리기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 오류제어
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 오류제어의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/오류제어.png" alt="오류제어">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 오류제어의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          종류
  단일-비트 오류, 다중-비트 오류, 집단 오류
유형 전후오반
  전진오류수정 (FEC) - 오류 복구를 위한 잉여 비트를 추가하여 전송하는 방식
  후진오류수정 (BEC) - 송신측에 오류 사실을 알려 재전송하여 복원하는 방식
  오류무시
  반향검사
기법 단다중해
  단일비트 - 오류 교정 원리는 잘못된 비트의 위치를 알아내는 것으로 패리티 비트 ASCII 코드는 3비트의 잉여 코드가 필요
  다중비트 - 데이터 비트의 집합을 중복하여 계산되는 중복 비트를 다중 비트 오류를 정정하는데 사용
  중복비트 - 주어진 데이터 비트의 수를 정정하기 위해 요구되는 중복 비트 수를 계산하기 위해 데이터 비트 수와 중복 비트 수 사이의 관계를 확인하는 방식
  해밍코드 - 해밍 코드에서 중복 비트의 위치를 알아내는 방식

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
