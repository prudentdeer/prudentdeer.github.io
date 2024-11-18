---
title: 트릴레마
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
      I. 블록체인의 세가지 딜레마, 블록체인 트릴레마
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 트릴레마의 정의
        </div>
        <div class="para-cntnt">
            블록체인에서 확장성, 탈중앙화, 보안성의 세가지 문제들이 서로 해결할 수 없는 상황  
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 트릴레마
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 트릴레마의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/트릴레마.png" alt="트릴레마">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 트릴레마의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          트릴레마 탈확보
  Decentralization (탈중앙화) - 제3자를 별도로 두지 않고 분산형 네트워크(P2P) 환경에서의 거래
  Scalability (확장성) - 사용자 수의 증대에 유연하게 대응하는 정도
  Safety (보안성) - 거래 데이터 조작 방지 및 무결성 보장   
사례    
  비트코인 - 탈중앙화와 보안성은 확보, 확장성의 한계
    - 탈중앙화와 보안에 초점을 맞춰 개발 되었으며 네트워크 확장에 따른 트랜잭션 속도에 대한 확장성 문제 발생   
  이더리움 - 확장성 한계로 트릴레마 발생
    - 확장성 한계 극복을 위해 이더리움 2.0 발표, 작업증명 방식의 대안으로 지분증명과 샤딩 기술 활용
  이오스 - 위임지분증명 (DPoS) 합의 알고리즘을 통해 탈중앙화와 확장성 해결
    - 위임지분증명 합의 알고리즘의 특성상 소수의 노드를 통해 합의가 이루어지기 때문에 탈중앙화 가치 저하
대안
  레이어1 스케일링 / PoW의 PoS 전환 - 이더리움 2.0 의 예 (작업증명 &gt; 지분증명)
  레이어2 도입 / 온체인, 오프체인 - 오프체인에서 코드를 실행하고, 결과값만 온체인에 기록, TPS 향상
  샤딩 / 블록체인 분할 - 블록체인 수평분할 후 부하 분산

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
