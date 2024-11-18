---
title: SLAM
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
      I. 자율주행을 위한 SLAM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SLAM의 정의
        </div>
        <div class="para-cntnt">
            자율주행 이동체가 주변환경지도를 작성하는 동시에 위치를 작성된 지도안에서 인식하는 매핑기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. SLAM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. SLAM의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/SLAM.png" alt="SLAM">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. SLAM의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 온오스덴노이
  유형
    Online SLAM - 실시간 지도작성, 현재로봇 위치 추정
    Offline SLAM - 전체이동경로 추정, 지도작성
  Visual SLAM 
    Sparse 알고리즘 - 영상의 feature point 매칭
    Dense 알고리즘 - 영상 전체 밝기 기반 매칭
  LiDAR SLAM 
    NDT 알고리즘 - voxel 공간을 인덱싱 처리 Normal Distributions Transformation
    ICP 알고리즘 - 다른 지점에서 스캔된 포인트 클라우드 정합 Iterative Closest Point
발생문제 / 해결방안
  위치추정 실패 / 센서 데이터 융합 - 칼만 필터링, AHRS(자세방위기준장치), INS(관성 항법 시스템) IMU(관성 측정장치) 센서데이터 융합 
  높은 계산비용 / 임베디드 GPU - 최적화 계산을 위한 높은 계산량 처리를 위한 임베디드 GPU 사용
  루프 폐쇄 / SLAM 번들조정 - 오차누적으로 인한 편차 해결 위해, 이전 방문 장소의 특징을 기억하여 위치추정 오류를 최소화하여 해결 
- 실내 공간이나 지하에서는 위치를 파악하기 위해 필수적

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
