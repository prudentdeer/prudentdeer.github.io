---
title: 페이징기법과 세그먼트기법의 비교
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
      I. Paging 기법과 Segmentation 기법의 비교
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 페이징기법과 세그먼트기법의 비교의 정의
        </div>
        <div class="para-cntnt">
            메모리를 고정된 크기의 프레임으로 선분할 후 주기억 장치에 사상시키는 메모리 할당기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 페이징기법과 세그먼트기법의 비교
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 페이징기법과 세그먼트기법의 비교의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/페이징기법과-세그먼트기법의-비교.png" alt="페이징기법과 세그먼트기법의 비교">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 페이징기법과 세그먼트기법의 비교의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          Segmentation 기법의 정의
  메모리가 각각 가변적인 세그먼트로 분할후 주기억장치에 사상시키는 메모리 할당기법
Paging 기법과 Segmentation 기법의 비교
  할당단위 - 프레임 &lt;&gt; 세그먼트
  할당크기 - 고정 크기 &lt;&gt; 가변 크기
  적재단위 - 프로그램 일부 &lt;&gt; 프로그램 전체
  데이터공유 - 분리되어 어려움 &lt;&gt; 데이터 공유 이점
  교체시간 - 짧음 &lt;&gt; 김
  쓰레싱 - 발생 &lt;&gt; 발생하지 않음
  단편화 - 내부 단편화 &lt;&gt; 외부 단편화
- 두 기법으로 인해 내 외부 메모리 단편화 발생
메모리 단편화의 해결방안 비교 단편화는 슬퍼
  유형 - 내부 단편화 &lt;&gt; 외부 단편화
  해결기법 - 슬랩할당자 &lt;&gt; 버디메모리
  상세기법 - 메모리 풀 구조이용 &lt;&gt; 메모리크기 분할 탐색
- Segment 별로 paging을 수행 Paged Segmentation 존재

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
