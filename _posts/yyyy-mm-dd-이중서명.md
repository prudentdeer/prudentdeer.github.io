---
title: 이중서명
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
      I. 구매와 지불 정보의 연접, 이중서명
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 이중서명의 정의
        </div>
        <div class="para-cntnt">
            구매 정보와 지불 정보를 다른 키로 암호화하여 연접하고, 개인키를 이용해 암호화하는 서명기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 이중서명
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 이중서명의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/이중서명.png" alt="이중서명">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 이중서명의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징
  이중 보안성 - 서명에 사용한 비밀키를 수신자의 공개키로 암호화
  개별 보안성 - 판매자는 구매내용만, PG사는 구매정보만 식별 가능
수행절차 구지연개
  구매정보 생성 - 구매정보 메시지 다이제스트 M1 생성
  지불정보 생성 - 지불정보 메시지 다이제스트 M2 생성
  연접 - 지불, 구매정보 연접하여 다이제스트 생성
  개인키 - 개인키를 이용하여 이중서명 생성
이중서명과 전자서명의 비교
  목적 - 보안성 강화 &lt;&gt; 부인방지 목적
  특징 - 지불, 구매정보 분리 &lt;&gt; 부인 방지
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
