---
title: BB84
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
      I. 대표적인 양자 키 분배 프로토콜, BB84 의 개요
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. BB84의 정의
        </div>
        <div class="para-cntnt">
            양자 키 분배 (QKD) 를 실현하기 위한 일회용 암호(OTP) 기반 무조건부 안전성이 보장되는 프로토콜
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. BB84
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. BB84의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/BB84.png" alt="BB84">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. BB84의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          동작원리
  광자의 편광을 이용하는 방식으로, 0 과 1 을 나타내는 편광을 각각 2 가지 정의한 다음, 십자 편광 필터와 대각 편광필터를 이용해 광자 측정
양자키 분배절차
  Alice 가 자신의 비밀키인 "0"과 "1"을 광자의 수직, 수평 상태 또는 ±45도 편광 기저 상태로 전환시킨다.
  Bob 이 Alice 의 광자를 받아서 기저 상태를 마구잡이로 선택하여 수직, 수평 상태 또는 ±45도 편광 기저로 광자를 측정한다.
  Alice 와 Bob 은 광자가 각각 어떤 기저 상태로 측정되었는지 공개적으로 논의한다.
  Alice 와 Bob 은 그들의 기저 상태가 일치한다고 동의한 비트들만 보관하여 선별키를 생성한다.
  마지막으로 그들은 자신들의 선별키 일부를 공개적으로 확인하며, 만일 선별키가 완전히 일치하지 않으면 제 3자인 Eve 가 엿들었다고 판단하고 모든 키를 버린다.

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
