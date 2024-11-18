---
title: RADAR
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
      I. 자율주행 자동차의 눈, RADAR
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. RADAR의 정의
        </div>
        <div class="para-cntnt">
            라디오파를 대상물에 발사해 되돌아오는 시간을 측정, 대상물까지의 거리, 속도를 측정하는 기술 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. RADAR
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. RADAR의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/RADAR.png" alt="RADAR">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. RADAR의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  거리 - 1m도 안 되는 거리의 물체부터 200m 이상 떨어진 물체까지 감지할 수 있음
  정밀도 - 낮음, 사물의 정확한 형체까지 인식하지는 못한다
  날씨조건 - 비, 안개, 눈 등 날씨에 강함
주요 알고리즘 CDT
  CFAR 알고리즘 - 노이즈제거, 표적반환 감지 적응형 알고리즘 (Constant False Alarm Rate) 
  DBF 알고리즘 - 특정 방향에서 강하게 반사되는 신호를 검사 (Digital Beamforming) 
  Tracking 알고리즘 - 지속적인 표적 탐지
RADAR 와 LIDAR 비교
  공통점 - 주변에 신호를 보내 감지되는 물체들에서의 반사시간을 통해 거리를 측정
  정밀도 - 낮음 &lt;&gt; 높음
  외부환경 - 비, 안개, 악천후에 강함 &lt;&gt; 날씨가 나쁘면 성능 떨어짐
  사용신호 - 라디오 전파 &lt;&gt; 레이저
  주행속도 감지 - LIDAR보다 성능 우수 &lt;&gt; RADAR보다 성능 떨어짐
  유효감지 거리 - LIDAR보다 2배 긴 거리 (최대 200m) &lt;&gt; RADAR보다 감지거리 짧음
  역할 - 물체와의 거리, 속도, 각도 측정, 충돌방지 &lt;&gt;  반경 360도 및 3D 정보 취득, 보행자감지

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
