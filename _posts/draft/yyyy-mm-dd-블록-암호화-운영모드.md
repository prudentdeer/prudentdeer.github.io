---
title: 블록 암호화 운영모드
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
      I. 블록 암호화의 운영모드
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 블록 암호화 운영모드의 정의
        </div>
        <div class="para-cntnt">
            블록암호화 운영을 위해 평문방식, 키스트림 방식 이용한 운영모드
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 블록 암호화 운영모드
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 블록 암호화 운영모드의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/블록-암호화-운영모드.png" alt="블록 암호화 운영모드">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 블록 암호화 운영모드의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          운영모드 ECCOC
  블록모드
    ECB - 가장 단순한 모드, 동일한 평문 블록 동일한 암호문 출력 / Electronic Codebook
    CBC - 보안 성이 제일 높은 모드, 다음 블록에 체인형태 영향 / Cipher Block Chaining
  스트림모드
    CFB - 암호문 자체를 피드백, 다음 블록에 피드백 처리  / Cipher Feedback
    OFB - 암호화의 결과를 피드백, 다음 블록에 피드백 처리 / Output Feedback
    CTR - 피드백 없이 넌스와 카운터를 사용 / Counter
5가지 비교
  패턴유지 - O X X X X
  초기벡터 - X O O O X
  오류전파 - X O O X X 

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
