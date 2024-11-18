---
title: 암호화
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
      I. 데이터의 보안 알고리즘, 암호화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 암호화의 정의
        </div>
        <div class="para-cntnt">
          &nbsp; 알고리즘과 암호화 키를 이용해 평문 형태의 메시지를 암호문으로 변환하는 과정
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 암호화
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 암호화의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/암호화.png" alt="암호화">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 암호화의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          암호화의 분류 스블공비대치
  정보단위의 분류
    스트림암호화 - 비트 단위로 암호화하는 방식, 속도 빠르고 오류파급효과 적음 / 실시간 스트리밍, MUX generator
    블록암호화 - 블록으로 나누어 블록 단위 암호화, 내용추가 어렵고 오류전파 / DES, AES, SEED 등
  키형태에 따른 분류
    공개키암호화 - 송수신자 각각 비밀키 보유 (비대칭키), 암호해독 어렵지만 느림 / DSA, RSA
    비밀키암호화 - 송수신자 공유한 비밀키 (대칭키)로 암호화, 구현용이하고 키 전달시 유출가능성 / AES, SEED
  암호화기술 분류
    대치암호 - 글자간 대체, 매핑 테이블을 이용한 일대일 교체, 
    치환암호 - 문자열의 위치를 변경, 서로 바꾸어 표현
암호화의 원리 대블치압혼확
  대체 - 글자간 대체, 매핑 테이블을 이용한 교체
  블록 - 평문을 블록으로 구성하고 단위 암호화
  치환 - 문자열의 위치를 변경, 서로 바꾸어 표현
  압축 - 문자열 중 일부를 삭제하여 용량의 감소
  혼돈과 확산 - 혼돈 - 상관관계 숨김 / 확산 - 암호특성 전파
  확장 - 무의미한 문자를 삽입하여 용량의 증가

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
