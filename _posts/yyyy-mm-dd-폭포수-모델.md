---
title: 폭포수 모델
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
      I. 고전적 개발 패러다임, 폭포수 모델
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 폭포수 모델의 정의
        </div>
        <div class="para-cntnt">
            SW개발의 계획, 운영, 유지보수까지 순차적으로 진행하며 단계별로 개발하는 하향식 개발방법론
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 폭포수 모델
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 폭포수 모델의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/폭포수-모델.png" alt="폭포수 모델">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 폭포수 모델의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            특징) 단계적, 순차적, Top-Down, 후반부 문제 발생 가능성 높음
프로세스 계요설개시운 단통시인설
  개발계획 - 문제정의, 타당성조사 등을 통한 프로젝트 영역 결정 / 프로젝트 관리계획서
  요구분석 - 프로젝트 영역과 사용자가 원하는 요구사항을 이해하는 단계 / 요구사항 정의서
  설계단계 - 분석모델을 가지고 세분화하여 구현할 수 있는 형태로 전환 / 설계서
  개발단계 - 설계단계에서 만들어진 설계서를 바탕으로 프로그램 개발, 단위테스트 진행 / 산출물
  시험단계 - 통합테스트, 시스템테스트를 통해 발생가능 오류를 발견하고 수정 / 테스트 결과서
  운영단계 - 실제 운영환경 구축 및 운영, 사용중 발생하는 오류 및 변화에 대응 / 결과물
폭포수모델과 프로토타입 비교
  개념 - 앞 단계 종료 후 다음단계 진행 &lt;&gt; 시제품 승인 후 본 제품 개발
  장점 - 요구사항이 명확하게 파악시 적합 &lt;&gt; 요구변경에 유연한 대응
  단점 - 요구변경에 대처가 어려움 &lt;&gt; 폐기시 매몰비용 발생
  적용분야 - 작은규모 프로젝트 &lt;&gt; 복잡한 시스템 개발

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
