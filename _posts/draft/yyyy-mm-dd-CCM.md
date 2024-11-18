---
title: CCM
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
      I. 전체 프로젝트 일정관리를 위한 CCM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CCM의 정의
        </div>
        <div class="para-cntnt">
            자원제약조건 고려하여 핵심적인 작업 파악하고, 필요한 자원 효율적으로 할당하는 일정개발기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. CCM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CCM의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/CCM.png" alt="CCM">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. CCM의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          납기지연법칙 후자파학
  파킨슨의 법칙 - 역설적으로 모든 작업은 빨리 끝낼 수 있어도 주어진 시간을 다 이용
  자기방어 - 작업을 일찍 완료하면, 다른 작업을 시키기 때문에 작업완료를 숨김
  후행공정 준비미흡 - 일찍 작업 완료해도 후속작업의 자원이 준비되지 않으면 일정 단축 못함
  학생 증후군 - 시험이 코앞에 다가와야 공부를 시작함. 닥치기 전까지는 일 시작 안함
버퍼의 종류 프피자, 안모행
  프로젝트 버퍼 - 프로젝트의 통합 버퍼 / CC의 끝 (안전영역, 모니터링영역, 행동영역)
  피딩 버퍼 - NCC에 여유를 위한 버퍼 / NCC끝
  자원 버퍼 - 작업착수 전에 해당자원에게 수행시기 노티 / -
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
