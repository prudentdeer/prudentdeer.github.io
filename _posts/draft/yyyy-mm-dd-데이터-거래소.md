---
title: 데이터 거래소
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 데이터베이스]
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
      I. 데이터경제 시작점, 데이터 거래소
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 거래소의 정의
        </div>
        <div class="para-cntnt">
            공급자와 수요자가 상호매칭하여 비식별정보, 기업정보 등 데이터 거래가능 중개플랫폼
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 데이터 거래소
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 데이터 거래소의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/데이터-거래소.png" alt="데이터 거래소">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 데이터 거래소의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 센카레심 플하오스
  데이터센터
    Kafka broker - 대용량 실시간 로그 처리에 특화
    Replica DB - Scale-out 제공을 위한 읽기 처리량 향상
    S3 API - HTTPS형태의 API로 데이터를 저장하거나 추출 (Simple Storage Service)
  플랫폼
    Sqoop - 대량의 RDB를 HDFS로 전송 후 분석 용이
    Object storage - 키 값과 데이터만 저장할 수 있는 확장성과 속도 우수
    Hadoop ecosystem - Data Lake에 최적화된 오픈소스 프레임워크
  제공방식 아파서
    API형 / 인터페이스 - 주기적 업데이트 상품
    파일형 / 텍스트, 엑셀 - 일회성 데이터 상품
    서비스형 / BI, 대시보드 - 서비스 형태의 상품
문제점과 해결방안  
  가격 불투명성
    가치평가 프로세스
    데이터 품질표시제
  데이터 부족
    비식별정보 허용 - 현재 가명, 익명 데이터만 거래가능
    마이데이터 연계
- 데이터 마스킹 및 익명화 기술 도입
- 디지털 서명 및 전자 인증서 적용
- 웹기반 원스톱 거래지원, 데이터거래소 2.0 개소
- 제공방식으로는 API, File, SaaS 존재

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
