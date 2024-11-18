---
title: 전이학습
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
      I. 유사분야 학습치 재사용, 전이학습
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 전이학습의 정의
        </div>
        <div class="para-cntnt">
            데이터부족 해결위해 Pre-Trained 학습치를 전이, 파인튜닝 기반 신경망 학습 재사용 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 전이학습
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 전이학습의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/전이학습.png" alt="전이학습">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 전이학습의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          프로세스 업다프파
  업스트림 태스크 - 먼저 이루어진 학습 (upstream) 
  다운스트림 태스크 - 모델이 전이되어 이루어지는 학습 (downstream) 
  프리트레인 - 업스트림 태스크를 학습하는 과정 (pretrain)
  파인튜닝 - 다운스트림 태스크를 학습하는 과정 (finetuning)
구성요소 과도 귀변자
  적용범위 
    과업전이 - 응용분야가 변경되는 경우, (이미지 분류, 음성 인식, 감정 분석)
    도메인전이 - 데이터 확률분포가 다른 경우 (의료 이미지, 뉴스 기사, 소셜 미디어 게시물)
  데이터셋 레이블 여부
    귀납 - 일반화된 모델을 만든 후 특화 Layer로 분리하는 방법
    변형 - Source data의 label을 이용하여 target data에 맞도록 학습
    자율 - Unlabeled Data 간 학습 진행
전이학습과 지식증류 비교
  도메인 - 유사도메인 &lt;&gt; 동일도메인
  데이터 - 대규모 &lt;&gt; 소규모
  특징 - 유사모델생성 &lt;&gt; 경량화
- 전이학습은 빠른학습과 오버피팅예방 위해 사용

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
