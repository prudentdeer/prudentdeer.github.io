---
title: NPKI, GPKI
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
      I. NPKI
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NPKI, GPKI의 정의
        </div>
        <div class="para-cntnt">
              전자서명법에 근거해 개인과 법인에게 인증서를 발급, 전자상거래를 대상 공개키기반 인프라
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. NPKI, GPKI
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. NPKI, GPKI의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/NPKI,-GPKI.png" alt="NPKI, GPKI">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. NPKI, GPKI의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            구성
    인증기관 - Root CA - KISA
    활용 - 일반거래, 은행, 증권, 무역
GPKI 
  정의 쥐정공행
    전자정부법에 근거해 행정기관 및 공무원에게 인증서를 발급, 행정업무 대상 공개키기반 인프라
  구성
    인증기관 - Root CA (행정안전부)
    활용 - Class 1 CA 전자서명, Class 2 CA 전자관인, 병무청, 대법원, 국회
NPKI 와 GPKI 비교
  근거법률 - 전자서명법 &lt;&gt; 전자정부법
  최상위인증기관 - KISA &lt;&gt; 행정안전부
  하위인증기관 - 6대 공인인증기관 &lt;&gt; 5대 정부 인증기관
  발급대상 - 개인 및 법인 &lt;&gt; 행정기관 및 공무원
  적용대상 - 전자상거래 등 &lt;&gt; 행정업무 등

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
