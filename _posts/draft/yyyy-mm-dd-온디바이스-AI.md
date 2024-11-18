---
title: 온디바이스 AI
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
      I. 엣지 디바이스와 AI 융합, 온디바이스 AI
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 온디바이스 AI의 정의
        </div>
        <div class="para-cntnt">
            클라우드 AI의 단점 - 인터넷 연결필요, 개인정보 문제, 비용문제, 대역폭제한, 지연제한 등
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 온디바이스 AI
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 온디바이스 AI의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/온디바이스-AI.png" alt="온디바이스 AI">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 온디바이스 AI의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          정의
  클라우드나 원격서버를 거치지 않고, 기기 로컬환경에서 AI 서비스를 실현하는 인공지능 기술
기술요소 이프양가 전지합신
  모델경량화
    이진화 - 가중치 0, 1로 표현하여 모델크기 축소
    프루닝 - 가중치 낮은 파라미터 0처리 가지치기 효과
    양자화 - 가중치 특정비트로 구간화하여 모델크기 축소
    가중치공유 - 근사한 값(코드북)을 통해 가중치들을 공유
  모델학습
    전이학습 - 유사한 유형의 모델로 학습결과 전이
    지식증류 - Teacher 모델에서 Student 모델 전이
    합성곱필터변경 - 합성곱필터 연산을 효율적으로 감소
    신경망가속기 - AI 연산을 효율적으로 수행하기 위한 하드웨어  
하드웨어
  HBM / PIM, PNM / NPU / 뉴로모픽칩 / SNN
장점 
  개인정보 - 기기 내부에서만 처리가 되기 때문에 데이터 유출 없음
  작동환경 - 인터넷 연결 없이도 작동이 가능
  응답시간 - 응답시간이 빠르고 네트워크 지연없이 실시간 응답이 가능
  비용절감 -
단점 
  발열문제 / 배터리문제 / 저전력화 / 성능저하
활용분야
  자율주행 자동차 - 교통 신호, 다른 차량, 보행자에 신속하고 실시간 대응
  지능형 CCTV -  머신러닝이 활동을 모니터, 중요한 이벤트만 클라우드에 전송
  산업 IoT - 잠재적 결함 모니터링하여 실시간 대응, 로컬 딥 러닝이 데이터 수집에도 기여
  이미지, 오디오 분석 - 실시간 이미지 인식, 오디오 트리거 반응
  실시간통역
  개인화서비스 
동향
  구글 / 제미나이 - 픽셀 폰에 탑재
  MS / 코파일럿 - LLM 탑재 및 BING 강화
  삼성전자 / 엑시노스 - 엑시노스9820으로 2019년 출시된 갤럭시 S10
  애플 / M3 칩 - 처음으로 AI 전용 칩 ‘뉴럴 엔진’을 탑재
- 온센서 AI, 온Things AI 로 발전예상

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
