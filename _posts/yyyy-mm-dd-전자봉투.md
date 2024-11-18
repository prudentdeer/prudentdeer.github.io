---
title: 전자봉투
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
      I. 전자봉투
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 전자봉투의 정의
        </div>
        <div class="para-cntnt">
            데이터는 비밀키를 이용해 암호화하고 비밀키를 수신자의 공개키로 암호화하여 전달하는 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 전자봉투
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 전자봉투의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/전자봉투.png" alt="전자봉투">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 전자봉투의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          생성절차
  메시지 다이제스트 / 해시함수 - 평문을 해시함수 이용 MD 생성
  비밀키 암호화 / 비밀키 - 비밀키 이용 MD 암호화
  전자봉투 생성 / 수신자 공개키 - 비밀키를 수신자 공개키로 암호화
  전자봉투 전송 / 평문, 암호문, 인증서 - 전자봉투에 3가지 요소 포함
개봉절차
  비밀키 해제 / 수신자 개인키 - 비밀키 해지시 수신자 개인키 이용
  암호문 해독 / 비밀키 - 해제된 비밀키로 MD 생성
  평문 해싱 / MD - 평문을 해싱하여 MD5 생성
  MD 비교 / 해싱비교 - 평문과 암호문 비교검증
전자봉투 사용기술
  해시암호 / MD5, SHA256 - 메시지 다이제스트 생성
  대칭키 암호화 / DES, ARIA, SEED - 블록암호화 이용
  비대칭키 암호화 / RSA, 디피헬만 - 수신자 부인방지

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
