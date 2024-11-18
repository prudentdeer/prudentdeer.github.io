---
title: IMDB
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
      I. In-Memory Database
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IMDB의 정의
        </div>
        <div class="para-cntnt">
            데이터의 저장, 연산을 디스크를 거치지 않고 모두 메인 메모리에서 처리하는 데이터베이스
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. IMDB
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. IMDB의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/IMDB.png" alt="IMDB">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. IMDB의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  속도 : 매체 접근 속도가 우수하고 단순한 알고리즘으로 적은 CPU 인스트럭션 수행
  성능예측 : 메인 메모리에 저장된 데이터를 접근하는 것은 성능 예측이 가능하여 즉각적인 응답 시간과 높은 처리량을 요구하는 실시간 환경 응용에 사용
  비용절감 : 메모리 데이터의 접근이라는 전체를 가지고 만들어진 인덱싱 기법을 이용하여 인덱스 크기를 줄이며 관리비용 절감
기술요소 티메압컬
  T-Tree 인덱스 : B 트리의 장점과 AVL 트리의 장점 결합, 데이터 접근 계산 최소화
  메모리 기반 : 데이터 접근 비용, 계산, 평가 비용이 디스크 대비 낮음
  압축기법 활용 : 인 메모리 DB의 데이터와 애플리케이션 간의 데이터 이동을 최소화시킴
  컬럼 지향형 Storage : Row-Based Storage는 데이터를 연속적인 row 데이터 형태로 저장하는 데에 비해서 연속적인 Column 데이터 형태로 저장
  Backup DB : 메모리 내부 데이터를 디스크에 백업용 동기화

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
