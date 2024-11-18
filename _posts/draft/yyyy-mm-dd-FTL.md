---
title: FTL
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 컴퓨터구조]
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
      I. SSD의 HDD 인터페이스. 플래시 변환계층
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. FTL의 정의
        </div>
        <div class="para-cntnt">
            OS 파일시스템의 논리섹터주소를 SSD의 물리블록과 페이지 주소로 변환하는 계층
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. FTL
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. FTL의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/FTL.png" alt="FTL">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. FTL의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            - SSD 플래시 메모리 특징을 숨기고 논리 블록 주소 지정을 제공
구성요소 스발 웨주가
  STL (Selector Translation Layer)
    Wear Leveling - 페이지당 Write 횟수를 모니터 하여 여러 블록에 균등하게 저장하는 기능
    주소매핑 - File system으로부터 논리적 주소를 NAND Flash Memory 물리적 주소로 연결
    가비지컬렉션 - 무효화된 페이지를 블록을 다른 블록에 복사한 후에 삭제하여 재사용 기능제공
  BML (Bad-block management Layer)
    공장 출하 시 초기 불량 블록과 사용 중 발생하는 불량 블록을 marking하여 관리하고 
    error 처리하는 기능 제공 - 순차적 쓰기 동작 중 배드 블록 발견 시 해당 블록을 배드 블록으로 표시하고 다음 블록으로 이동 후 계속 쓰기작업
  LLD (Low Level Driver)
    NAND Flash를 사용하기 위한 Driver 인터페이스 제공
GC, Wearleveling 동작위한 오버프로비저닝
  내부 오버프로비저닝 / 자체내장 - 출시될 때부터 SSD 자체에 내장된 공간
  외부 오버프로비저닝 / 공간할당 - 프로그램을 통해 설정하거나 자동으로 공간 할당
- SSD의 성능감소와 수명단축 문제 개선

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
