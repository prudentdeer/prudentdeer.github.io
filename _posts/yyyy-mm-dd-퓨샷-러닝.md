---
title: 퓨샷 러닝
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 인공지능]
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
      I. 인간처럼 효율적 학습, 퓨샷 러닝
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 퓨샷 러닝의 정의
        </div>
        <div class="para-cntnt">
            적은 양의 데이터를 가지고 새로운 작업이나 Domain을 학습하기 위한 기계학습 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 퓨샷 러닝
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 퓨샷 러닝의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/퓨샷-러닝.png" alt="퓨샷 러닝">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 퓨샷 러닝의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 NK서쿼 제원퓨
  학습데이터
    N way - class의 수, 고양이/토끼/햄스터
    K shot - class 당 데이터의 수
  Dataset
    Support Set - 새로운 클래스에 대한 학습 데이터
    Query Set - 새로운 클래스에 대한 평가 데이터
    Meta-Train Dataset - Meta-Test를 잘 수행하기 위해 메타러닝에 쓰이는 학습 데이터
    Meta-Test Dataset - Support set + Query set 
  학습종류
    Zero Shot / K = 0 - 한번도 관측되지 않은 클래스학습
    One Shot / K = 1 - 하나의 샘플만 주어지는 학습
    Few Shot / K &gt; 1 - 클래스별 소수 샘플로 학습
Zero-shot, One-shot, Few-shot 비교
  개념 - 샘플 X &lt;&gt; 하나의 샘플 &lt;&gt; 몇개의 샘플
  목표 - 일반화 &lt;&gt; 단일 예에서 일반화 &lt;&gt; 작은예제에서 일반화

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
