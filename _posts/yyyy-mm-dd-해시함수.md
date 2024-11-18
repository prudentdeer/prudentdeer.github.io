---
title: 해시함수
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
      I. 무결성 보장 위한 해시함수
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 해시함수의 정의
        </div>
        <div class="para-cntnt">
            역상저항, 제2역상저항, 충돌회피성을 갖고, 임의길이 입력에 고정길이 암호문 출력 알고리즘
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 해시함수
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 해시함수의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/해시함수.png" alt="해시함수">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 해시함수의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징 압효역역충
  압축성 - 임의의 길이 문자열을 고정된 길이의 문자열로 변환
  효율성 - 어떤 입력 값에 대해서도 계산이 빠름
  1차 역상저항성 - H(x) = y 만족하는 x를 찾는 것이 어려움
  2차 역상저항성 - H(x) = H(x’), x ≠ x’을 만족하는 x’를 찾는 것은 불가능
  충돌저항성 - H(x) = H(x’)인 임의의 값 x, x’ 찾기 불가능 
해싱기법 나폴중기
  나눗셈법 - 키를 버킷의 크기로 나누고, 나머지 값을 주소로 사용
  폴딩법 - 키 값을 여러 방식으로 접어 값을 합산한 값을 주소로 사용
  중간제곱 함수 - 키 값의 중간 N자리를 뽑아서 제곱한 후 상대 번지로 사용
  기수 변환 - 주어진 레코드 키를 특정한 진법의 수로 간주하고 키를 변환
보안취약점 레브 솔패키
  Rainbow Table - 해시함수 사용하여 만들어낼 수 있는 값들을 대량으로 저장한 표
  Brute Force - 조합 가능한 모든 문자열을 하나씩 대입해 보는 방식의 공격
보안강화 방안
  Salt / 데이터베이스 - 해싱값에 무작위 솔트값을 추가하여 데이터베이스에 저장하는 복잡도 증가방법
  Pepper / 하드코딩 - 솔트가 DB에 저장되는 취약점을 개선, 하드코딩된 랜덤값을 해싱값에 추가하는 방법
  Key stretching / 재귀해싱 - 해시된 값을 또 다시 해시 함수의 입력 값으로 넣어 해싱을 반복하는 방법
- Salt와 Pepper, 키스트레칭 이용 Rainbow table 이용 bruteforce 공격 방어

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
