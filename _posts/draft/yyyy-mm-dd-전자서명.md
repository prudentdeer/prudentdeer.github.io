---
title: 전자서명
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
      I. 부인방지를 위한, 전자서명
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 전자서명의 정의
        </div>
        <div class="para-cntnt">
            무결성과 신원인증, 부인방지를 위해 송신자의 개인키로 암호화하고 공개키로 복호화하는 서명기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 전자서명
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 전자서명의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/전자서명.png" alt="전자서명">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 전자서명의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  인증성 - 문서가 변경되지 않았음을 검증, 무결성이 보장
  부인방지성 - 문서에 대한 서명을 부인할 수 없도록 보장
  무결성 - 문서가 서명된 이후에는 변경될 수 없음
  안전성 - 정보가 유출되거나 변조될 위험이 없음
  효율성 - 물리적 문서에 비해 관리가 용이
과정 해전데복검
  송신자 / 해싱적용 - 메시지에 대한 해시함수 적용
  송신자 / 전자서명 - A의 개인키로 해시메시지 암호화
  전   송 / 데이터전송 - 메시지와 서명된 메시지 전송 
  수신자 / 복호화 - A의 공개키로 서명된 메시지 복호화
  수신자 / 검증 - 복호화한 해시값과 해시화 메시지의 비교
이중서명과 전자서명의 비교
  목적 - 지불, 주문정보 분리 &lt;&gt; 사용자증빙 및 부인방지
  특징 - 연접 &lt;&gt; 부인 방지
  사례 - SET (신용카드 지불 프로토콜) &lt;&gt; 공인인증서
  주요기술 - 비밀키, 공개키, 개인키, 해시, 전자서명 &lt;&gt; 송신자의 공개키, 개인키, 해시

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
