---
title: TCAM
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
      I. 3진 메모리 셀에 기반한 TCAM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. TCAM의 정의
        </div>
        <div class="para-cntnt">
            0, 1, X의 3가지 입력을 활용해 단일클록 주기에서 전체내용을 검색하는 특수 고속메모리
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. TCAM
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. TCAM의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/TCAM.png" alt="TCAM">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. TCAM의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          활용사례 애큐라대 인정모시
  네트워크
    ACL 검색 - IP 주소, 포트 번호 등과 일치하는 규칙을 찾기 위해 사용
    QoS 설정 - 패킷의 특정 특징(예: DSCP, ToS 비트)과 일치하는 규칙을 찾는 데 사용
    라우팅테이블 - IP 주소 또는 서브넷과 관련된 라우팅 테이블을 검색
    대역폭 할당 - 특정 서비스에 대한 대역폭을 할당하는 데 활용
  데이터베이스
    인덱싱 - 데이터베이스의 인덱스 가속화
    정규식 - 특정 패턴을 가진 문자열 또는 이진 데이터를 검색
  보안
    모니터링 - 악성코드, 침입을 감지하고 차단
    시그니처 탐지 - IDS, IPS 시그니처 식별
TCAM과 BCAM 비교
  연산자 - 0, 1, X &lt;&gt; 0 또는 1
  검색 - 패턴검색 &lt;&gt; 일치검색
  응용 - 네트워크 장비, 라우터, 스위치 &lt;&gt; 메모리, 캐시, 컴퓨터 아키텍처에서 사용
- TCAM의 와일드카드 X로 인해 뛰어난 패턴매칭

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
