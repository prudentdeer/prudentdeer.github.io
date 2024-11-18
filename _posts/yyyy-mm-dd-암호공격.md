---
title: 암호공격
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 보안]
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
      I. 제3자가 암호 해독 시도 공격, 암호 공격
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 암호공격의 정의
        </div>
        <div class="para-cntnt">
            암호통신에서 제 3자가 암호문으로부터 평문을 찾으려는 시도를 하는 암호해독 공격
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 암호공격
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 암호공격의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/암호공격.png" alt="암호공격">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 암호공격의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          지식기반 공격기법 기암평암
  기지평문공격 KPA - 암호문과 평문의 관계로부터 키나 평문을 추정, Known Plaintext Attack
  암호문공격 COA - 공격자가 암호문만 가지고 공격하는 유형, Ciphertext Only Attack
  선택평문공격 CPA - 평문을 선택하여 암호문을 얻어 키나 평문을 추정, Chosen Plaintext Attack
  선택암호문공격 CCA - 암호문에 대한 평문을 얻어 암호를 해독, Chosen Ciphertext Attack
정보단위기반 차선연 구예키
  블록암호
    차분 공격법 - 비선형 함수에 대한 입력차분 출력차분의 확률 분포가 비 균일함 이용
    선형 공격법 - 중복입력에 대한 선형 근사식을 증명함으로써 암호문 단독 공격이 가능
    연관키 공격법 - 서로 다른 2개의 키 사이의 연관 관계를 알고 발생된 평문/암호문 쌍을 가지고 키를 알아내는 방법
  스트림암호
    구별 공격 - 키 스트림과 난수열을 구별하는 공격 
    예측 공격 - 키 스트림을 획득하였다는 가정하에 다음 발생할 수열을 예측하는 형태의 공격 
    키복구 공격 - 키 스트림을 이용하여 마스터 키 또는 내부 상태 값을 복구하는 공격 
    대수적 공격 - 과포화된 다변수 연립 방정식을 이용하여 공격

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
