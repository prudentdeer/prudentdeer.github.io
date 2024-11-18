---
title: Queue
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 자료구조]
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
      I. FIFO 방식의 구조, 큐
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Queue의 정의
        </div>
        <div class="para-cntnt">
            한쪽 끝에서 Enqueue, 다른한쪽 끝에서 Dequeue 이루어지는 FIFO 형식의 선형 자료구조
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. Queue
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. Queue의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/Queue.png" alt="Queue">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. Queue의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          유형 선원링
  선형 큐 - 단순 선형구조 / 크기제한, 재사용불가 
  원형 큐 - 처음과 끝 연결 / 길이제한, 재사용가능
  링크드 큐 - 포인터 연결 / 메모리 할당과 해제 필요 
문제점 재재고
  재사용 불가 - 인출발생 데이터 공간 재사용 불가능
  재배치 비용 - 공간 재사용위해 요소 이동시 비용발생
  고정된 길이 - 초기 지정큐 사이즈 이상 활용불가 

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
