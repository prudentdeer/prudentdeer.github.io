---
title: RFID
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
      I. 무선 주파수를 이용하여 대상을 식별하는 기술, RFID
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. RFID의 정의
        </div>
        <div class="para-cntnt">
            마이크로칩 내장 태그에 저장된 데이터를 무선주파수를 이용하여 리더에서 자동 인식하는 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. RFID
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. RFID의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/RFID.png" alt="RFID">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. RFID의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 호리안태
  호스트 - 한개 또는 다수의 태그로부터 읽어 들인 데이터를 처리함, 에이전트 기반의 분산 계층 구조
  리더 - 주파수 발신을 제어하고 태그로부터 수신된 데이터를 해독 
    저주파 - 30KHz ~ 500KHz 저주파를 사용
    고주파 - 850MHz ~ 950MHz 또는 2.4GHz ~ 2.5GHz 구간
  안테나 - 무선주파수를 발사하며 태그로부터 전송된 데이터를 수신하여 리더로 전달
  태그 - 상품에 부착되며 데이터가 입력되는 IC 칩과 안테나로 구성, 데이터를 무선으로 리더에 전송
    Passive - 내외부로부터 별도의 전원공급이 없음
    Active - 내장 배터리를 사용하는 방식
RFID vs NFC 비교
  연결범위 : 100m &lt;&gt; 10cm
  통신 : 단방향 &lt;&gt; 양방향
  장점 : 장거리 인식가능 &lt;&gt; 높은 보안성
  속도 : 빠름, 멀티처리 &lt;&gt; 느림, 한번에 1건

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
