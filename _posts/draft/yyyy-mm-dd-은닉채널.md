---
title: 은닉채널
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
      I. 은닉채널
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 은닉채널의 정의
        </div>
        <div class="para-cntnt">
            기본 채널에 기생하는 통신채널로, 은닉 메시지를 채널에 속이거나 삽입해서 전달하는 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 은닉채널
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 은닉채널의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/은닉채널.png" alt="은닉채널">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 은닉채널의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 헤확 프패터스
  사용하지 않는 헤더 - 추후 사용하기 위해 예약해둔(Reserved) 영역을 이용
  확장기능 및 패딩 - 추가될 기능을 충분히 고려하지 못하였기 때문에 보안에 잠재적인 위협
  프로토콜 필드 - 프로토콜 명세에 정의된 필드를 임의의 값으로 수정
  패킷전송 타이밍 - 전송된 패킷의 시간 간격이나 패킷 유실을 이용한 낮은 속도의 은닉 채널을 구성
  터널링 - 한 프로토콜을 다른 프로토콜로 전환하는 과정 중에 은닉 채널을 삽입
  스테가노그래피 - 사진, 음악, 동영상 같은 일반적인 파일 안에 데이터를 숨김

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
