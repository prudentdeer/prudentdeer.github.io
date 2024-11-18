---
title: 부채널 공격
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 보안]
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
      I. 부채널 공격
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 부채널 공격의 정의
        </div>
        <div class="para-cntnt">
            보안모듈이 발동될 때 물리적으로 발생하는 소리, 전력, 연산시간을 분석해 암호키 탈취하는 공격기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 부채널 공격
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 부채널 공격의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/부채널-공격.png" alt="부채널 공격">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 부채널 공격의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          공격기법 시음전파 로템차
  시차분석 공격 / 연산시간차 - 인터넷 암호화 시스템 중 하나인 RSA의 연산 시간을 분석해 암호키를 추론
  음향분석 공격 / CPU동작, 키보드소리 - CPU, 키보드, 프린터 소리 분석
  전력분석 공격 / 정적소모, 동적소모 - 정적소모와 동적소모 이용 해밍무게 이용 암호 유추
  전자기파 공격 / 위상분석, 파형분석 - 수행중 발생 주파수 패턴인식, 범주화
  로우해머 공격 - DRM 메모리 칩의 설계 결함을 이용
  템페스트 공격 - 모니터 등에서 발생하는 EMF 전자파를 훔치는 공격
  잔존데이터 공격 - 데이터 삭제 뒤 남은 잔여물을 활용
  차분오류 해석 - 연산 과정에 의도적인 오류를 일으키는 공격
대응방안 마블알 무특
  물리적
    무작위성기법 - 무작위 클럭 이용
    특수케이스 - 전자파 유출 최소화
  기술적
    마스킹기법 - 연산시 중간값 숨김, 마스킹값 교체
    블라인딩기법 - y = f(x) 계산시 x, y 블라인드 계산
    알고리즘 수정 - 대기시간추가, 우회연산

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
