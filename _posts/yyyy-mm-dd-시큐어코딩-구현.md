---
title: 시큐어코딩 구현
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 필수암기]
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
      I. 보안취약점을 최소화하기 위한 시큐어코딩
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 시큐어코딩 구현의 정의
        </div>
        <div class="para-cntnt">
            안정성과 신뢰성확보를 위해 소스코드 개발 단계에서 주요보안 취약점을 고려한 개발방법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 시큐어코딩 구현
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 시큐어코딩 구현의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/시큐어코딩-구현.png" alt="시큐어코딩 구현">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 시큐어코딩 구현의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          적용대상
  행정기관 및 공공기관 정보시스템 감리대상 정보화사업
적용범위 입보시에코캡에
  입력데이터 검증 및 표현 / SQL 삽입, 자원 삽입 등 19개
    - 프로그램 입력값에 대한 검증 누락 또는 부적절한 검증, 데이터의 잘못된 형식 지정으로 인해 발생할 수 있는 보안 약점
  보안기능 / 부적절한 인가, 중요한 자원에 대한 잘못된 권한허용 등 17개
    - 보안기능을 적절하지 않게 구현 시 발생할 수 있는 보안약점
  시간, 상태 / 경쟁조건, 제대로 제어되지 않은 재귀 등 3건
    - 동시, 거의 동시 수행을 지원하는 병렬 시스템
    - 하나 이상의 프로세스가 동작하는 환경에서 시간 및 상태를 부적절하게 관리하여 발생
  에러처리 / 오류 메시지 통한 정보 노출, 오류 상황 대응 부재 등 3개
    - 에러를 처리하지 않거나, 불충분하게 처리하여 에러정보에 중요정보가 포함되어 발생
  코드오류 / 널 포인터 역참조, 부적절한 자원 해제 등 9개
    - 타입변환 오류, 자원의 부적절한 반환 등과 같이 개발자가 범할 수 있는 코딩 오류로 인해 유발
  캡슐화 / 제거되지 않고 남은 디버그 코드, 시스템 데이터 정보 노출 등 2개
    - 중요한 데이터 또는 기능성을 불충분하게 캡슐화 했을 때 인가되지 않은 사용자에게 데이터 누출이 가능
  API 오용 / DNS Lookup에 의한 보안결정, 위험하다고 알려진 함수 사용 등 5건
    - 의도된 사용에 반하는 방법으로 API를 사용하거나 보안에 취약한 API를 사용하여 발생

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
