---
title: 스핀락
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
      I. 루프상태 임계구역 진입, 스핀락 개요 - OS 레벨
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 스핀락의 정의
        </div>
        <div class="para-cntnt">
            임계영역의 동시성제어 위해 임계구역 진입이 가능할 때까지 Busy waiting 상호배제 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 스핀락
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 스핀락의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/스핀락.png" alt="스핀락">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 스핀락의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징 비문
  Busy waiting - 동기화 상황에서 권한 획득을 위한 과정에서 일어나는 현상
  문맥교환 제거 - 문맥교환이 일어나지 않아 문맥교환 제거 가능
매커니즘 획제획잠
  획득 / free Spinlock 획득 - 공유자원 접근위해 스핀락 획득 
  재시도 / 자원 요청 스피닝 - free spinlock을 얻을때까지 반복해서 요청, 캐리플래그 0 확인
  획득 / Spinlock 획득 - 공유자원 락 해제하면 다른 스피닝이 스핀락 획득, 캐리플래그 0 일시 진입
  잠금해제 / Release spinlock - 임계영역 진입 후 다시 lock 반납 / 캐리플래그를 다시 1로 세팅
스핀락과 세마포어 비교
  핵심 - 루프 재시도 &lt;&gt; 세마포어 변수
  구현 - IRQL 상승 &lt;&gt; P연산, V연산
  고려사항 - 무한대기 상태 &lt;&gt; 문맥교환 발생

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
