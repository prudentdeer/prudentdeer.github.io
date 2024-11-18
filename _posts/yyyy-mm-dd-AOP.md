---
title: AOP
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
      I. OOP 한계보완, AOP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. AOP의 정의
        </div>
        <div class="para-cntnt">
            관심사 분리원칙 기반, 의존성주입, JointPoint, Weaving 이용 관점지향 개발방법론
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. AOP
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. AOP의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/AOP.png" alt="AOP">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. AOP의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  모듈화 - 횡단 관심사를 포괄적이고 체계적으로 모듈화
  의존성 주입 - 객체 또는 구성요소 간의 종속관계를 소스코드로 설정하지 않고 외부의 설정파일을 통해서 주입
  단순화 - 핵심 모듈은 더 이상 횡단 관심사의 모듈을 직접 포함하지 않으며 횡단 관심사의 모든 복잡성은 Aspect 로 분리
  캡슐화 - 횡단 관심사는 Aspect 라는 새로운 단위로 캡슐화하여 모듈화가 이루어짐
구성요소 핵횡 조포어위애타
  관심사
    핵심관심사 - 단일 모듈이 가지는 주된 요구사항 / Business Logic
    횡단관심사 - 여러 개 모듈에 공통적 사용되는 부가적인 요구 사항 / 로그, 보안, 인증, 결제 등
  프로그래밍 요소
    Joint Point - Advice 를 적용할 수 있는 시점 혹은 호출 이벤트
    Point Cut - 여러 Joint Point의 집합체로, 관심사가 어디에 적용될 것인지를 지정
    Advice - Joint Point 에서 실행되야 하는 소스코드, 어떤일을 할지에 대한것의 구현체
    Weaving - Advice를 해당 지점에 주입하는 과정, Joint Point들을 Advice로 감싸는 과정
    Aspect - Pointcut 과 Advice 를 합쳐 놓은 클래스 형태의 코드
    Target - Advice 받는 클래스
기대효과
  개발측면 - 모듈화 / 재사용성 / 확장성개선
  관리측면 - 유지보수성 / 트렌젝션 / 로깅관리
AOP 와 OOP 비교
  개념 - 관점중심 &lt;&gt; 객체중심
  특징 - 관점과 관심사 (Aspect, Concern) &lt;&gt; 캡추다정상
  스타일 - 추상적, 선언적 &lt;&gt; 구체적, 명시적
  활용 - 보안, 로깅, 인증 &lt;&gt; 개발, 객체모델링
- OOP 추구 모듈화, Loosly Coupled 지원이 핵심

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
