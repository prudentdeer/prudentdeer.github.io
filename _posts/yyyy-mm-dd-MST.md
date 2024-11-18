---
title: MST
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
      I. 마그네틱 간편결제, MST
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MST의 정의
        </div>
        <div class="para-cntnt">
            마그네틱 신용카드와 동일한 자기장을 발생시켜 신용카드정보 결제단말기에 전달하는 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MST
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MST의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MST.png" alt="MST">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MST의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          결제방식
  1. 마그네틱 카드를 리더기에 긁게 되면 카드에 내장된 카드번호와 유효기간 등의 정보가 자기장으로 변환되어 전송
  2. 이 정보를 받은 카드사가 이를 승인하여 결제가 완료
장점
  마그네틱 보안 전송 기술은 기존 마그네틱 결제 단말기를 교체할 필요 없이 편리하게 모바일 결제를 이용
단점
  마그네틱 기술의 최대 단점은 보안성이 취약함 (자기장 신호를 해석&amp;복사의 문제점)
대표 서비스 - 삼성페이 
개발 - 삼성전자가 인수한 미국의 루프페이
절차 - 앱실행 &gt; 인증 &gt; 단말기 태그
신호 - 마그네틱 정보를 자기장으로 변환
방식 - 비접촉식
국내 보급률 - 90% 이상
단말기 교체 - 필요없음
수수료 - 수수료 0%
취약점 - 마크네틱 카드 불법복제
보안 - 일회용 가상카드 정보 생성(자동 소멸) 

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
