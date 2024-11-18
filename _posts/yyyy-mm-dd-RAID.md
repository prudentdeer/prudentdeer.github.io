---
title: RAID
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
      I. 고가용성과 성능 향상 위한, RAID
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. RAID의 정의
        </div>
        <div class="para-cntnt">
            성능향상과 안정성 확보위해 여러 개의 디스크에 중복 저장, 분산 저장하는 스토리지 솔루션
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. RAID
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. RAID의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/RAID.png" alt="RAID">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. RAID의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          RAID 유형 스미 비바블 디더
  RAID 0 (Striping) - 중복 저장 없이 여러 디스크에 데이터를 분산 저장, Striping 기반의 병렬 디스크 구성 기법
  RAID 1 (Mirroring) - 패리티를 사용하지 않지만 데이터 디스크를 동일하게 복사한 미러 디스크로 구성된 RAID
  RAID 2 (Parity bit) - 스트라이핑으로 구현하고, 오류 정정을 위한 Hamming code를 사용
  RAID 3 (Parity byte) - 스트라이핑 기술을 사용하여 디스크들을 구성하고, 별도의 디스크에 패리티 정보를 저장
  RAID 4 (Parity block) - 블록 형태의 스트라이핑 기술과 패티리 사용
  RAID 5 (Distributed parity) - 블록 스트라이핑과 분산된 패리티를 사용
  RAID 6 (Double distributed parity) - 패리티 2개를 디스크 저장
  RAID 0 + 1 (Striping + Mirroring) - RAID 0(Striping) 구성 후 RAID 1(Mirror) 구성
  RAID 1 + 0 (Mirroring + Striping) - 4개 이상의 디스크를 2개씩 RAID 1로 구성하고, 다시 RAID 0으로 구성
HDD RAID 와 SSD RAID 비교
  읽기/쓰기 - 느림 &lt;&gt; 매우 빠름
  안정성 - 높음 &lt;&gt; 매우 높음
  초기비용 - 낮음 &lt;&gt; 높음
  전력소비 - 높음 &lt;&gt; 낮음
  복구가능성 - 높음 &lt;&gt; 낮음
- SSD 가격하락과 속도차이로 인해 SSD 레이드 사용확장

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
