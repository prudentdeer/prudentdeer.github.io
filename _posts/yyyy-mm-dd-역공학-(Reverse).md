---
title: 역공학 (Reverse)
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
      I. 개발 단계를 역으로 올라가 문서 도출, 역공학
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 역공학 (Reverse)의 정의
        </div>
        <div class="para-cntnt">
            개발 단계를 역으로 기존시스템의 코드나 데이터로부터 아이디어나 설계기법 등을 도출하는 방법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 역공학 (Reverse)
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 역공학 (Reverse)의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/역공학-(Reverse).png" alt="역공학 (Reverse)">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 역공학 (Reverse)의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          필요성
  기존 시스템에 대한 유지보수성 확보, 변경에 따른 시스템 효율성 제고
  메인 프레임에 대한 다운사이징 개발 시 필요, 시스템과 일치하는 문서를 생성 정보 획득 가능 
입/출력
  INPUT - 원시코드, 목적코드, 작업 제어 절차, 라이브러리, 디스크 디렉토리, 텍스트 자료, 데이터베이스 구조, 각종 문서     
  OUTPUT - 구조도, 자료 흐름도, 제어 흐름 그래프, 개체 관계도, 자료 흐름 그래프
주요기법 역논자
  논리 역공학 / 설계정보 - 원시코드로부터 정보를 추출하여 물리적 설계 정보 저장소에 저장, 물리적 설계 정보를 얻어내는 역할 수행
  자료 역공학 / 데이터 - 기존 DB를 수정하거나 새로운 DB 관리 시스템으로 이전하는 역할 수행

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
