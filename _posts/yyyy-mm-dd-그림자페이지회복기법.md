---
title: 그림자페이지회복기법
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
      I. Shadow Table 이용 회복, Shadow Paging 회복기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 그림자페이지회복기법의 정의
        </div>
        <div class="para-cntnt">
            트랜잭션 시작시 하드디스크에 Shadow 테이블 생성, 동기화하고 장애발생시 활용하는 회복기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 그림자페이지회복기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 그림자페이지회복기법의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/그림자페이지회복기법.png" alt="그림자페이지회복기법">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 그림자페이지회복기법의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  백업 데이터 - 트랜잭션 내용의 스냅샷인 백업 테이블 활용
  병행 적용 - 다중 트랜잭션 발생 시,로그기반이나 검사점 기법과 병행 적용 필요
상세설명
  정상동작
    - 트랜잭션 수행 중 현재 페이지 테이블과 그림자 페이지 테이블을 운용
    - 현재 페이지 테이블을 우선 갱신하고, 트랜잭션 종료 시 그림자 페이지 테이블 갱신
  회복동작 - 장애 발생 시, 그림자 페이지 테이블의 내용을 이용하여 회복 수행
  장점 - 별도의 로그 처리 필요 없어 상대적으로 낮은 부하
  단점 - 페이지 테이블 관리 필요, 상대적으로 높은 저장 공간 요구

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
