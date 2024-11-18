---
title: 하이퍼 파라미터
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
      I. 하이퍼 파라미터
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 하이퍼 파라미터의 정의
        </div>
        <div class="para-cntnt">
            딥러닝모델 정확도 향상위해 인간의 선험적 지식기반 모델에 사용자가 직접설정하는 변수
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 하이퍼 파라미터
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 하이퍼 파라미터의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/하이퍼-파라미터.png" alt="하이퍼 파라미터">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 하이퍼 파라미터의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          튜닝기법 매그랜배 휴단모시 랜범최함
  Manual Search
    휴리스틱조합 - 사용자의 직관과 경험 기반 탐색
    단순성적용 - 사용자 도출 조합 중 최적 조합 적용
  Grid Search
    모든조합 탐색 - 하이퍼파라미터 적용값 전체 탐색
    시행횟수 한계 - 하이퍼파라미터 증가로 인해 전수 탐색 한계
  Random Search        
    랜덤샘플링 - 범위 내 무작위 값 반복 추출
    범위부여 - 하이퍼파라미터 최소/최대값부여
  Bayesian
    최적화 - 관측 데이터 기반 F(x) 추정
    함수생성 - 확률 추정 결과 기반 입력값 후보 추천 함수
종류 정배가은 조드학훈
  모델튜닝
    정규화 - 모델과적합 방지, 안정성향상        
    배치크기 - 한번에 처리하는 데이터 수
    가중치초기화 - 모델 가중치 초기화
    은닉층 - 뉴런수, 용량, 복잡성 영향
  학습튜닝
    조기종료 - 손실감소 적을때 중지, 과적합 방지
    드랍아웃 - 과적합 방지, 일부뉴런무시
    학습률 - 동적조절, 수렴속도 최적화
    훈련횟수 - 에포크, 반복훈련 횟수
파라미터, 하이퍼파라미터 비교
  주체 - 알고리즘 &lt;&gt; 인간
  조정가능 - 불가 &lt;&gt; 가능
  종류 - 편향, 가중치 &lt;&gt; 에포크, 배치사이즈 등

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
