---
title: 교착상태
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 운영체제]
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
      I. 무한 자원대기, 교착상태
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 교착상태의 정의
        </div>
        <div class="para-cntnt">
            멀티 프로세스간 자원 점유상태에서 서로 상대자원 요구하며 기다리는 무한 대기상태
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 교착상태
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 교착상태의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/교착상태.png" alt="교착상태">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 교착상태의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          발생원인 상점비환
  상호배제 / 배타점유 - 자원을 배타적으로 점유하여 다른 프로세스가 사용하지 못함
  점유와 대기 / 부분할당 - 자원을 점유하고 있으면서 다른 자원을 요구
  비선점 / 선점불가성 - 할당된 자원은 사용이 끝날 때까지 강제로 빼앗을 수 없으며, 자신만이 해제 가능
  환형대기 / 원형대기열 - 프로세스간 자원요구가 하나의 원형을 구성
  - 4가지 모두만족시 교착상태 발생 / 하나이상 제거해 해결
해결방법 예회발복
  예방 
    상점비환 부정 - 교착상태 발생원인, 조건들의 부정
  회피 
    은행가 알고리즘 - 자원상태 감시 / 수 관리 알고리즘
    Wait-die, wound-wait - 타임스탬프 기반 회피기법
  발견
    자원할당 그래프 - 프로세스와 자원간 관계 그래프
    대기 그래프 - 규칙에 의해 edge 소거 그래프
  회복
    프로세스 kill - 프로세스 강제 종료
    자원선점 - 선점한 자원 다른 프로세스 할당
- 대표적 예 철학자만찬

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
