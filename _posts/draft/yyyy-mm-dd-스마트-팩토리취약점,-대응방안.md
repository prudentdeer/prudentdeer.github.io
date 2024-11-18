---
title: 스마트 팩토리취약점, 대응방안
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
      I. 보안이 어려운 이유 
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 스마트 팩토리취약점, 대응방안의 정의
        </div>
        <div class="para-cntnt">
            제조설비 전용 통신프로토콜 사용
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 스마트 팩토리취약점, 대응방안
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 스마트 팩토리취약점, 대응방안의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/스마트-팩토리취약점,-대응방안.png" alt="스마트 팩토리취약점, 대응방안">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 스마트 팩토리취약점, 대응방안의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            임베디드 SW 탑재로 적용 한계
  생산설비 교체주기가 10년이
보안취약점
  OT
    센서 - 공장내 물리적 접근 장치훼손
    액추에이터 - 펌웨어 취약점 / DOS 공격 오동작 / 도청 / 운전중단
    PLC - 백도어 / 역공학 / 소스오류 / 비안가자 접근 / 데이터 변조 / 설정값 변경
  IT
    업무PC - 비인가 저장매체 / 이메일 / 스파이웨어
    HMI - 불법접근 / 랜섬웨어 감염 / USB 악성코드 / 외부인터넷 바이러스
    MES - 악성코드 전파 / 원격접속 / SW 취약점
보안대책 모법보감 출시업물 인접암네

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
