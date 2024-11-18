---
title: 정보은닉
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
      I. 정보은닉 Information Hiding
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 정보은닉의 정의
        </div>
        <div class="para-cntnt">
            내부 구현정보, 데이터 보호위해 은닉개체의 공용 인터페이스로만 접근가능한 특징
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 정보은닉
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 정보은닉의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/정보은닉.png" alt="정보은닉">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 정보은닉의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징        
  복잡성 제거 : 외부에는 불필요한 내부적으로만 사용되는 부분을 감춰서 복잡성을 줄임
  Data 보호 : 외부로부터 데이터를 보호하기 위함
  정보은닉 : 캡슐화 방법으로 class 내부 정보를 은닉하고, 접근 제한 단계를 부여하는 특징
  데이터 보호, 응집도 증가, 결합도 감소
구현방법 업캡인추
  업캐스팅 - 자식 객체의 타입을 부모 객체의 타입으로 형변환
  캡슐화 - 객체의 필드 및 메소드 은닉
  인터페이스 - 공개 메소드를 은닉 메소드들과 구분하고 통합적으로 관리
  추상화 - 객체의 공통적인 특성과 동작을 추출하여 추상 클래스 정의
- SOLID 원칙기반 설계, OOP 구현

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
