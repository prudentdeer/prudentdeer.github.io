---
title: 적대적공격
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
      I. 머신러닝 알고리즘 취약점, AI 적대적공격
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 적대적공격의 정의
        </div>
        <div class="para-cntnt">
            머신러닝 모델의 취약점을 공격하여 오류를 발생시키거나 모델을 악용하는 공격기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 적대적공격
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 적대적공격의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/적대적공격.png" alt="적대적공격">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 적대적공격의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          적대적 공격유형
  무결성 공격 PEIE
    Poisoning Attack - 악의적인 학습 데이터를 주입
    Evasion Attack - 학습 데이터에 노이즈를 추가
  기밀성 공격
    Inversion Attack - 쿼리전송 후 학습 데이터 유추
    Extraction Attack - 쿼리전송 후 머신러닝 모델 유추
적대적 공격 방어기법 DGDA
  수동적 방어
    Distillation - 결과값들이 학습정보를 제공하지 못하도록 보완
    Gradient Masking - Gradient가 출력으로 노출되지 않도록 난독화 처리
  능동적 방어
    Defense GAN - 입력 데이터를 통해 GAN을 실시하여 적대적 예제의 노이즈를 제거
    Adversarial Training - 적대적샘플을 학습데이터 셋에 포함시켜 공격에 대한 내성향상

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
