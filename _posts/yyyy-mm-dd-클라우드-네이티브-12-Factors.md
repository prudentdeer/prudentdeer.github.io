---
title: 클라우드 네이티브 12 Factors
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 디지털서비스]
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
      I. 클라우드 네이티브 개발원칙, 12 Factors
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 클라우드 네이티브 12 Factors의 정의
        </div>
        <div class="para-cntnt">
            포트바인딩 - 애플리케이션은 독립적이며 ,http 같은 포트 바인딩 통해 외부에 서비스 제공
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 클라우드 네이티브 12 Factors
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 클라우드 네이티브 12 Factors의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/클라우드-네이티브-12-Factors.png" alt="클라우드 네이티브 12 Factors">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 클라우드 네이티브 12 Factors의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            동시성 - 애플리케이션을 수평적으로 확장하며, 무상태 특성이 단순하게 만듦
  빌드, 릴리즈, 실행 - 빌드, 릴리즈, 실행단계를 엄격히 분리
  프로세스 – 애플리케이션 실행시 하나 혹은 여러개의 무상태 프로세스로 실행
  폐기가능 – 빠른 시작과 안정적 종료를 통한 안정성 극대화
  백엔드서비스 - 애플리케이션 작동에 필요한 서비스를 연결된 리소스로 취급
  설정 – 소스코드와 설정정보를 분리, 실행시 코드에서 읽어서 사용
  개발/운영환경일치 - 개발/검증/운영 환경을 가능한 비슷하게 유지
  종속성 - 패키지, 라이브러리 등 종속이 필요한 경우 명시적 선언하고 분리
  로그 - 로그파일을 이벤트 스트림으로 취급하여 이를 취합, 인덱싱, 분석
  코드베이스 - 하나의 코드베이스로 버전관리 하며, 이를 여러곳에 배포
  운영관리 프로세스 - 시스템 관리작업은 일회성 프로세스로 만들어서 실행

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
