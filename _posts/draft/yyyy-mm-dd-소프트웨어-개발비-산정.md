---
title: 소프트웨어 개발비 산정
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
      I. 소프트웨어 개발비 산정
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 소프트웨어 개발비 산정의 정의
        </div>
        <div class="para-cntnt">
            사전준비 - 요구사항 명확화, 계산방법 간이법 결정
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 소프트웨어 개발비 산정
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 소프트웨어 개발비 산정의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/소프트웨어-개발비-산정.png" alt="소프트웨어 개발비 산정">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 소프트웨어 개발비 산정의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            기능점수산정 - 데이터기능 (ILF, EIF), 트랜젝션기능(EI, EO, EQ) 로 구분해서 총기능점수 산정
  보정전개발비 산정 - 기능점수 x FP (605,784) 
  보정후개발비 산정 - 보정전 개발비 X 규연성운보 (없으면 1로 가정)
  직접경비, 이윤산정 - 직접경비 0, 이윤 25%
  SW개발비 산정 - 개발원가 + 직접경비 + 이윤
보정계수 규연성운보  
  규모 - 사업규모의 증가에 따른 생산성 변화에 대한 보정
  연계복잡성 - 대상 애플리케이션의 연계 기관수가 증가함에 따른 프로젝트 관리의 복잡성
  성능요구 - 응답시간 또는 처리율에 대한 사용자 요구수준의 복잡성
  운영호환성 - 응용SW의 설치 운영환경의 상이한 정도
  보안성 - 시큐어코딩, 웹취약점점검, 암호화점검, 개인정보보호 등 보안성에 대한 요구수준
구성요소
  개발원가 - 기능점수로 측정되는 소프트웨어 개발규모 x 기능점수당 단가 x 보정계수
  직접경비 - 해당 소프트웨어 개발사업에 소요되는 직접적인 경비
    시스템 사용료, SW 사용료, 지급이자, 전문가 비용, 여비, 특수자료비, 인쇄, 청사진비, 자료조사비
  이윤 - 개발원가의 25% 이내에서 계산

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
