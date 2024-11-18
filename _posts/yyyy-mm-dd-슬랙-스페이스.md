---
title: 슬랙 스페이스
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
      I. &lt;증거분석을 위한 핵심기법, 슬랙 스페이스 분석의 개요&gt;
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 슬랙 스페이스의 정의
        </div>
        <div class="para-cntnt">
            파일 시스템은 하나의 큰 파일을 저장할 때 여러 클러스터들로 나누어 저장하게 된다. 이 때 가장 마지막 클러스터에는 파일의 가장 뒷부분을 저장한 다음 남는 공간이 생길 수 있는데 이를 슬랙 스페이스라 한다.
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 슬랙 스페이스
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 슬랙 스페이스의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/슬랙-스페이스.png" alt="슬랙 스페이스">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 슬랙 스페이스의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          &lt;구조도&gt; 와 분석방법
  하드디스크에는 파일을 저장 할 때 생기는 파일 슬랙 스페이스, 하드 디스크의 할당되지 않은 공간들과 볼륨 슬랙 스페이스, 파티션 슬랙 스페이스 등이 존재
  이런 슬랙 스페이스에 데이터를 숨겨 놓을 수 있으며 파일 테이블에서는 이런 슬랙 스페이스를 인식하지 못하기 때문에 의도적인 데이터의 은폐, 은닉이 가능
  이런 슬랙 공간을 검색하기 위해서는 슬랙 공간을 검색할 수 있는 포렌식 툴을 사용
  디스크에서 슬랙 스페이스 크기와 위치를 검사하고 디스크의 물리적 주소를 파악하여 해당 섹터의 정보를 검색

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
