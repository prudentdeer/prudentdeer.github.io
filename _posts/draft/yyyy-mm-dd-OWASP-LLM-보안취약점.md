---
title: OWASP LLM 보안취약점
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
      I. LLM 보안위험 최소화 위해 취약점에 대한 인식제고, 대응전략 제안하기위한 보안취약점 목록
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. OWASP LLM 보안취약점의 정의
        </div>
        <div class="para-cntnt">
              예방조치 - 입력검증, 정제, 맥락인식 필터링, 출력인코딩, 파인튜닝
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. OWASP LLM 보안취약점
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. OWASP LLM 보안취약점의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/OWASP-LLM-보안취약점.png" alt="OWASP LLM 보안취약점">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. OWASP LLM 보안취약점의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
            2. 데이터 유출 - LLM의 답변을 통해 민감정보, 기밀정보 유출
    예방조치 - 출력필터링, 맥락인식, 차등정보보호, 데이터익명화, 감사
  3. 부적절한 샌드박싱  - LLM 환경이 다른 시스템/데이터와 격리되지 않은 상태
    예방 조치 - 격리, 접근제한, 정기적 감사, 검토
  4. 무단코드 실행 - 악성코드, 명령 또는 동작을 실행하도록 악용
    예방조치 - 입력검증, 정제, 샌드박싱, 기능제한
  5. 서버측 요청위조 - 의도치 않은 요청수행, 내부 서비스, API 또는 데이터 저장소 접근
    예방조치 - 입력검증, 정제, 네트워크/애플리케이션 보안 설정
  6. 과도한 의존 - 오해, 부정확 정보확산, 사람 제시 의견감소, 비판적 사고 축소 
  7. 부적절한 AI 정렬 - 바람직하지 않은 결과나 취약점으로 이어지는 경우
    예방조치 - 목적과 행동 정의, 시나리오, 입력값, 문맥 테스트와 검증
  8. 불충분한 접근통제 - 잠재적 취약점 악용 가능성
    예방조치 - MFA, 접근통제
  9. 부적절한 오류처리 - 오류, 디버깅 통해 민감정보, 잠재적 공격벡터를 위협 행위자에게 노출
    예방조치 - 오류처리 메커니즘, 오류 메시지 사용을 고려
  10. 학습데이터 중독 - 보안, 유효성 또는 윤리적 행동을 손상, 학습 데이터나 미세조정 절차 조작
    예방조치 - 무결성 보장, 취약점과 편향 제거
- 생성형 AI 안전한사용은 기업의 책임, 정보보호와 신뢰성 확보 위해 노력 필요
원문보기:
https://www.itworld.co.kr/news/293983#csidx5f61586b371727fab885dea7465256e 

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
