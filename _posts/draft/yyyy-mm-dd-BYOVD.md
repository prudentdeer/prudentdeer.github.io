---
title: BYOVD
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
      I. 드라이버 취약점 공격, BYOVD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. BYOVD의 정의
        </div>
        <div class="para-cntnt">
            윈도우에서 하드웨어 공급업체의 취약한 드라이버 모듈을 통해 시스템의 접근권한을 얻는 공격기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. BYOVD
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. BYOVD의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/BYOVD.png" alt="BYOVD">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. BYOVD의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          공격절차
  시스템접근 - APT 이용 취약한 드라이버를 찾기 위하여 시스템에 접근 
  권한상승 - 공격자가 시스템 내 자신의 사용자 또는 프로세스 권한 상승 
  취약드라이버 설치 - 취약한 드라이버 설치 시 시스템 공격 준비 
  커널구조 수정 - 시스템의 커널 구조를 수정하여 액세스 권한 획득 
  보안제어 무력화 - 공격자는 시스템에 설치된 보안 제어를 무력화시켜 공격 수행
대응방안
  차단
    취약드라이버 차단 - 설치하지않도록 해시 차단
    윈도우 업데이트 - 지속 드라이버 목록 업데이트
  서명
    MS 서명드라이버 - 서명검증 통한 필터링
    평가 및 검증 - 지속적 평가 및 시뮬레이션

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
