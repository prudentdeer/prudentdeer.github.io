---
title: MIV
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
      I. 메타버스 구현을 위한 MIV
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MIV의 정의
        </div>
        <div class="para-cntnt">
            시청자가 공간상에서 6DoF 자유도로 움직일 때 보여져야 할 영상을 재현하는 비디오기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. MIV
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. MIV의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/MIV.png" alt="MIV">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. MIV의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 티비 뮤비 프리포
  Encoder 
    TMIV Encoder - 텍스처, 기하정보 이용 공간상의 중복성 제거, 아틀라스 인코딩 포맷 생성
    Video Encoder - 아틀라스 기반 HEVC 또는 VVC 비디오 코덱을 통해 압축 전송
  Decoder 
    MIV Decoder - 시청자의 움직임에 따라 동적으로 끊어짐 없이 뷰포트영상을 재생
    Video Decoder - 비트 스트림 데이터 아틀라스 형식으로 MIV decoder로 전달
  6DoF (Degree of Freedom)
    Pre Processing - 3D 비디오 인코딩의 효율적 압축
    Post Processing - 중간시점영상 합성 통해 뷰포트 영상재생
부복호화 표준기술 프패아랜
  인코더 
    푸루닝 (pruning) - 기하정보를 이용해서 모든 픽셀 3D 공간상으로 역투영
    패치패킹 - 다수의 시점영상들을 기하정보들을 통해 공간상에 매핑
  단말
    아틀라스 패치 점유지도 - 메타데이터를 파싱하여 픽셀별로의 패치정보를 기록
    랜더러 (Renderer) - 중간시점의 영상을 합성, 뷰포트 영상으로 제공

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
