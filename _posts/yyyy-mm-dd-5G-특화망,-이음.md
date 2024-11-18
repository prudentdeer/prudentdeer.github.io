---
title: 5G 특화망, 이음
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 네트워크]
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
      I. 5G 이음, 5G 특화망
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 5G 특화망, 이음의 정의
        </div>
        <div class="para-cntnt">
            특정 지역에 한해 5G 서비스에 특화된 NPN, MEC 기술 기반의 5G 서비스 전용 네트워크
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 5G 특화망, 이음
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 5G 특화망, 이음의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/5G-특화망,-이음.png" alt="5G 특화망, 이음">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 5G 특화망, 이음의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소
  Control Plane
    AMF - 5G 네트워크 단말 이동성관리
    SMF - 5G 네트워크 세션제어기능
    PCF - 컨트롤 플레인 기능의 정책제공
    NSSF - Network slice 선택 돕기위한 정보, 슬라이스 구성정보
  User Plane
    UDF - 패킷전송, 외부네트워크 연결, 트래픽 과금위한 보고기능 등
  5G 기지국
    RU - 원격무선신호 RF 처리장치
    DU - 디지털 데이터 처리장치
    CU - UE와 기지국간 통신 제어
모델유형
  자가구축
    On-Premise - 이통사나 SI사와 무관히 기업이 직접 이음5G망 설계, 구축
  사업자구축
    On-Premise - 이음 5G 사업자가 구성요소(5G 코어, 5G 기지국, MEC)를 구축, 관리
    5G Core 제어부공유 - 이음 5G사업자가 센터의 5G Core 제어부를 운영, 모니터링
    5G Core 전체공유 - 이음 5G사업자가 센터의 5G 코어, 장비 운영, 모니터링
안전성, 신뢰성 확보방안
  네트워크 보안인증 – CC인증, 보안적합성검증, KCMVP
  기지국 이중화 – 가상셀, RU교번배치, CU 이중화
  전송망 이중화 - 지역특화망 및 본사 코어망구축, 통신사업자 공유
  예비전원 확보 - 축전지 활용, 비상발전, 연동 연료전지

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
