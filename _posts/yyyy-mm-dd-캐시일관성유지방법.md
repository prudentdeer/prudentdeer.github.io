---
title: 캐시일관성유지방법
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
      I. 캐시일관성 유지방법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 캐시일관성유지방법의 정의
        </div>
        <div class="para-cntnt">
            다중프로세스 환경에서 로컬캐시와 공유 메모리간 불일치문제 방지, 일관성 유지하는 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 캐시일관성유지방법
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 캐시일관성유지방법의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/캐시일관성유지방법.png" alt="캐시일관성유지방법">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 캐시일관성유지방법의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          불일치 원인 공멀입통
  내부적요인
    공유변수 사용 - 하나의 변수를 참조할 때
    멀티 프로세서 - 여러 프로세스가 동시에 작업
  외부적요인
    입출력 동작 - 입출력 동작 중에 외부에서 변경
    통신부재 - 캐시메모리 간 통신부재, 전달 미흡
해결방법 
  SW 기법 캐변
    공유캐시 사용 - 모든 프로세스가 하나의 cache 사용, 구조 간단, 프로세스간 충돌 심함
    공유변수 미사용 - 공유변수를 cache 에 저장하지 않음, 성능저하 야기
  HW 기법 버스갱무 디풀리체 스메비
    버스감시 기반
      Snoopy Controller - 프로세스들의 기억장치 처리동작을 감시
      쓰기갱신 - 공유블록 갱신하는 경우, 다른 모든 캐시에 갱신되는 정보가 보내짐
      쓰기무효 - 다른 캐시 쓰기 발생 시 자기 정보 무효화
    디렉토리 프로토콜
      Full Map Directory - 데이터에 대한 Directory 를 주기억 장치에 저장하고 디렉토리에 데이터에 대한 블록을 가진 캐시를 가리키는 포인터와 상태가 저장
      Limit Directory - Full Map Directory 를 작게 유지
      Chained Directory - Directory 포인터를 Linked List 로 연결, 분산식
    스누피 프로토콜  
      MESI 프로토콜 - 변경된 캐시 스누피 제어기가 다른 스누피 제어기에게 변경된 내용 통보
      VI 프로토콜 - 프로세서가 캐시 데이터 수정 시 주기억장치로 갱신

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
