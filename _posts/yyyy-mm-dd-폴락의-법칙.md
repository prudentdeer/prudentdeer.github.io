---
title: 폴락의 법칙
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
      I. CPU에서 GPU시대의 방향성 제시, 폴락의 법칙
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 폴락의 법칙의 정의
        </div>
        <div class="para-cntnt">
            개별 코어당 파이프라인 수, 멀티쓰레딩과 트랜지스터 수, 전력소비는 비례한다는 법칙
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 폴락의 법칙
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 폴락의 법칙의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/폴락의-법칙.png" alt="폴락의 법칙">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 폴락의 법칙의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          원리
  연산처리 강화 - 반도체의 성능은 면적(복잡도)이 2배 증가할 때 1.4배 증가하며, 또한 전력소모는 면적에 비례
  연산처리 병렬화 - 성능향상을 위하여 병렬로 효과적 연산처리
발전방향
  멀티코어 - 개별 프로세서의 성능 향상보다는 복수 개의 프로세서 코어를 이용 
  이기종 프로세서화 - 기존의 고기능 다용도 프로세서 코어와 데이터 처리전용 프로세서 내장
- 같은 공정에서 두 배 정도의 복잡도(=두 배의 면적, 두 배의 소비 전력)를 가지게 설계해도 성능 향상은 2의 제곱근, 즉 1.4배정도 밖에 안 되더라
- 폴락의 법칙으로 CPU코어에 2배의 트랜지스터를 써도 성능은 제곱근인 1.4배만 항상

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
