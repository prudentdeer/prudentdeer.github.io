---
title: CAPCHA
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
      I. 역 튜링테스트, CAPTCHA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CAPCHA의 정의
        </div>
        <div class="para-cntnt">
            컴퓨터가 사람과 봇을 구별하기 위해 난독 텍스트, 이미지를 이용 봇 판별 프로그램
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. CAPCHA
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. CAPCHA의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/CAPCHA.png" alt="CAPCHA">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. CAPCHA의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 텍오리 노원슬
  모달리티 기반
    텍스트 캡차 - 난독 텍스트 기반
    오디오 캡차 - 문맹, 난독증, 시각장애, 노인위해 개발
    리캡차 - 두 단어를 함께 제시해 답변을 요구하는 캡차 / 프로젝트 구텐베르크, 플라톤의 항연
  행위기반
    노캡차 리캡차 - 이미지를 손으로 클릭해 답변을 제출
    원클릭 캡차 - 체크박스를 만들어 두고, 마우스 포인터를 움직이는 패턴을 감지
    슬라이드 캡차 - 수평바를 드래그해 이동하는 패턴
인공지능 접목, ReCAPTCHA v3
  이용자의 특정 행동 없이 백그라운드에서 봇 여부를 판단하여 사용자의 행동 점수화 (봇0~1사람)
  기술
    이중 인증(2FA) - 점수가 낮으면 추가 인증요구
    행동점수화 - 0 ~ 1 범위의 점수측정
- v3는 사용자 차별, UX 방해없는 보안성 강화기능 제공

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
