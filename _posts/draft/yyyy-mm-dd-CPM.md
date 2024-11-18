---
title: CPM
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 프로젝트관리]
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
      I. 의존관계 계산을 통한 일정개발, CPM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CPM의 정의
        </div>
        <div class="para-cntnt">
            개별활동들을 연결하여 순방향 분석과 역방향 분석을 통해 CP 도출하는 일정개발기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. CPM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CPM의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/CPM.png" alt="CPM">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. CPM의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          절차
  활동정의 - 활동순서배열 - 활동기간산정 - 전진계산 - 후진계산 - 주경로분석 - 수행기간추정
구성요소
  CP - 여유기간이 0 인 경로를 연결한 경로
  ES (Early Start) - 빠른 개시일
  EF (Early Finish) - 빠른 종료일
  LF (Late Finish) - 늦은 종료일
  LS (Late Start) - 늦은 개시일
  FF (Free Float) - 자유 여유시간
  TF (Total Float) - 한 활동이 가질 수 있는 총 여유시간 &lt; 다이어그램
계산방법
  전진계산
    ES (Early Start) - 선행활동의 빠른 종료일 (EF) + 1
    EF (Early Finish) - 빠른 개시일 (ES) + 기간 - 1
  후행계산
    LF (Late Finish) - 후행활동의 늦은 개시일 (LS) - 1
    LS (Late Start) - 늦은 종료일 (LF) – 기간 + 1
  여유시간
    FF = 후행 활동의 빠른 개시일 (ES) - 빠른 종료일 (EF) – 1 (1일 시작기준)
    TF = 늦은 종료일 (LF) – 빠른 종료일 (EF) or 늦은 개시일 (LS) – 빠른 개시일 (ES) &lt; 다이어그램
CCM 과 CPM 의 비교
  시작일 - LS &lt;&gt; ES
  기간계산 - 여유시간을 고려해 산정 &lt;&gt; 선후관계 고려해 계산
  관리관점 - 전체 버퍼의 소진율 &lt;&gt; EVM 을 통한 예측
  여유시간 - 버퍼로 통합관리 &lt;&gt; 활동별 반영

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
