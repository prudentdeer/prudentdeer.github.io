---
title: 혼잡제어
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 네트워크]
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
      I. 네트워크 신뢰성 보장, TCP 혼잡제어
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 혼잡제어의 정의
        </div>
        <div class="para-cntnt">
            네트워크 TCP 혼잡상황 발생을 감지하고 윈도우 크기제어를 통한 오버플로우 방지기법 
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 혼잡제어
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 혼잡제어의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/혼잡제어.png" alt="혼잡제어">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 혼잡제어의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  Slow Start - 네트워크 연결 추가에 윈도우 사이즈를 2의 지수배로 증가
  Congestion Avoidance - ACK 수신 시 마다 윈도우 사이즈를 지수 증가에서 선형 증가로 변경
  Fast Retransmit - 윈도우 사이즈를 현재의 1/2까지 감소, 사이즈를 절반에서 다시 시작
  Fast Recovery - 윈도우 사이즈를 절반에서 다시 선형적으로 증가
혼잡상황 감지
  중복응답 / 3 Duplicate ACK - 동일 패킷에 대하여 ACK를 3번 피드백 받은 상황
  임계초과 / Timeout - 일정 시간내에 패킷이 도달하지 않아 최대 대기시간을 초과한 상황
혼잡상황 제어
  Tahoe - 동일하게 처리
    패킷손실이 발생하지 않아 안전성 높음 / 이미 수신한 패킷을 다시 수신
    3 Duplicate ACKs / Timeout - 윈도우 사이즈 1, ssthresh는 윈도우 크기의 절반
    - 윈도우사이즈가 1부터 시작하기때문에 느림, Reno 가 해결
  Reno - 다르게 처리
    하나의 패킷 손실이 발생한 경우에 가장 좋은 성능 / 타임아웃이 발생할 확률이 높음
    3 ACK Duplicated - 윈도우 크기 1/2, ssthresh 줄어든 윈도우 값으로 설정
    TimeOut - 윈도우 사이즈 1, ssthresh 값은 동일
  New Reno - SS + CA + Fast retransmit + 개선된 Recovery
  TCP Vegas / 윈도우 사이즈 조정 - SS + CA + Fast retransmit + 선택적 재전송
  AIMD -  윈도우의 크기를 1씩 증가시켜가며 전송, 실패하면 윈도우 크기를 반으로 줄임
혼잡윈도우 크기
  Tahoe / 3 Dup Acks / Timeout
    Slow Start / ACK를 받을 때마다 2배로 증가
    Congestion Avoidance / ssthresh 부터는 1씩 증가
    Fast Retransmit - window 사이즈 1 로 , ssthresh는 윈도우 크기의 절반
    Fast Recovery - ssthresh 까지 2배씩 증가
  Reno / 3 Dup Acks / Timeout
    Slow Start / ACK를 받을 때마다 2배로 증가
    Congestion Avoidance / ssthresh 부터는 1씩 증가
    Fast Retransmit - window size 1/2 / window size 1, ssthresh 줄어든 윈도우 값으로 설정
    Fast Recovery - ssthresh 까지 1씩 선형증가

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
