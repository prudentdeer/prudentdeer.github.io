---
title: Auto Scaling
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
      I. 탄력적인 클라우드 자원 활용, Auto scale
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Auto Scaling의 정의
        </div>
        <div class="para-cntnt">
            예측불가 클라우드 서비스 부하대응위해 메트릭지표, 로드밸런서 이용 자동 증설/회수 기술
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Auto Scaling
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Auto Scaling의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Auto-Scaling.png" alt="Auto Scaling">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Auto Scaling의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 모알로인 씨네디로
  구성요소 
    모니터링 - CPU 사용률, 네트워크 Mbps(In/Out), PPS(In/Out) 등의 다양한 부하
    알람 -  지정한 임계치 조건을 벗어나는 것(이상/이하/초과/미만)을 감지
    로드밸런서 - 부하 분산과 인스턴스 확장 관리
    인스턴스 - 부하 발생 시 확장이 필요한 서비스 인스턴스를 그룹으로 설정
  메트릭지표
    CPU 사용량
    NW 패킷
    Disk I/O        
    Load Average - 1분, 5분, 15분, 1시간, 6시간 단위
Scale Up &lt;&gt; Scale Out &lt;&gt; Scale In 비교
  정의 - 리소스 업그레이드 &lt;&gt; 리소스 확장 &lt;&gt; 리소스 축소
  특징 - 수직적 확장 &lt;&gt; 수평적 확장 &lt;&gt; 수평적 축소
  장점 - 확장 용이 &lt;&gt; 고가용성, 부하 분산 &lt;&gt; 비용 절감
  단점 - 고비용, 한계존재 &lt;&gt; 관리 및 구성 복잡성 &lt;&gt; 스케일링 시간 지연
- 변화하는 워크로드의 요구사항에 즉각 대응할 수 있음

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
