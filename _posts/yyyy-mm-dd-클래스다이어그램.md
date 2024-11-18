---
title: 클래스다이어그램
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 소프트웨어공학]
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
      I. 객체 타입과 관계 표현, 클래스 다이어그램
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 클래스다이어그램의 정의
        </div>
        <div class="para-cntnt">
            시스템에서 사용되는 객체 타입을 정의하고 그들간의 관계를 표현한 정적 다이어그램
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 클래스다이어그램
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 클래스다이어그램의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/클래스다이어그램.png" alt="클래스다이어그램">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 클래스다이어그램의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          접근제어자 클속연 퍼프디프
  + public - 어디서든 접근가능
  - private - 같은 클래스 내에서만 접근가능
  # protected - 동일 패키지거나 상속관계 하위 객체만 접근가능
  ~ default - 동일 패키지 객체만 접근가능
관계표현 연직집복의일실
클래스 다이어그램과 유스케이스 다이어그램 비교
  사용목적 - 개발자 설계용 &lt;&gt; 사용자와 개발자의 소통
  관계표현 - 정적 다이어그램 &lt;&gt; 동적 다이어그램
  특징 - 즉시개발, 코딩활용 &lt;&gt; 공통화된 모델링형태

가. 교사(Teacher)는 하나 이상의 여러 과목(Course)을 가르칠 수 있다. 
나. 각 과목(Course)은 시간표 상 슬롯(Slot)에 수업시간(Time)과 교실(Room)이 할당되어 있다. 

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
