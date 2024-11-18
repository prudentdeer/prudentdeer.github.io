---
title: 전송부호화 기법
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
      I. 아날로그 정보의 효율적 디지털화, 전송 부호화 개요
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 전송부호화 기법의 정의
        </div>
        <div class="para-cntnt">
            아날로그 형태 정보를 디지털 형태로 효율적 변환을 위한 수학적 매핑 및 변환 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 전송부호화 기법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 전송부호화 기법의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/전송부호화-기법.png" alt="전송부호화 기법">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 전송부호화 기법의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          소스코딩 (Source Coding)
  정보의 효율적 전송 위해 아날로그 데이터를 디지털 변환, 불필요정보제거, 압축 전송기법
채널코딩 (Channel Coding)
  정보의 안정적 전송 위해 소스코딩 변환신호를 오류 검출, 재전송 지원 하는 전송기법
라인코딩 유포비
  수신측의 동기재생과 오류검출 위해 디지털 데이터를 디지털 신호로 변환하는 기법
  Unipolar : 하나의 전압 레벨만 사용
  Polar : 2개의 전압레벨 사용
  Bipolar : 3개의 전압레벨 사용함
소스코딩과 채널코딩의 비교 허무런 리컨터
  목적 : 아날로그 신호압축 &lt;&gt; 전송에러 정정
  역할 : 불필요 정보 제거 &lt;&gt; 오류의 검출
  형태 : 아날로그 - 디지털 &lt;&gt; 디지털 - 디지털
  대상 : JPEG, MPEG, WAV, MP3 &lt;&gt; 소스코딩된 압축데이터
  종류 : FLC (고정길이부호화), VLC (가변길이부호화) &lt;&gt; FEC, BEC
  기법 : 허프만 코딩, 무손실압축, 런렝스 코딩 &lt;&gt; Reed solomon, Convolutional, Turbo code
- 라인코딩은 작은 대역폭과 높은 전력 가지도록 설계

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
