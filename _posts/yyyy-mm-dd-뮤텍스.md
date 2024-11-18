---
title: 뮤텍스
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
      I. 상호배제를 이용한 동기화 기법, 뮤텍스 - OS 레벨
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 뮤텍스의 정의
        </div>
        <div class="para-cntnt">
            임계영역의 동시성제어 위해 Locking과 Unlocking 사용 1개의 스레드 대상 상호배제 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 뮤텍스
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 뮤텍스의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/뮤텍스.png" alt="뮤텍스">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 뮤텍스의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          주요기술 락언락
  Lock - 임계영역 접근수행
  Unlock - 임계영역 접근해제
- 뮤텍스를 소유하고있는 스레드가 이 뮤텍스를 해제
- 뮤텍스는 세마포어가 될 수 없음

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
