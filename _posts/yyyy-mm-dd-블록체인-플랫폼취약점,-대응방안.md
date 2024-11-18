---
title: 블록체인 플랫폼취약점, 대응방안
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 디지털서비스]
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
      I. 보안위협
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 블록체인 플랫폼취약점, 대응방안의 정의
        </div>
        <div class="para-cntnt">
              키도난 및 분실 : 분실된 키가 악용될 경우 자산 및 기밀거래 메시지 유출
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 블록체인 플랫폼취약점, 대응방안
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 블록체인 플랫폼취약점, 대응방안의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/블록체인-플랫폼취약점,-대응방안.png" alt="블록체인 플랫폼취약점, 대응방안">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 블록체인 플랫폼취약점, 대응방안의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
              취약한 키 생성 : 키 재생성 공격이 가능할 경우 자산 및 기밀거래 메시지가 유출 가능
    블록체인 S/W 취약점 : 키 도난, 합의 조작, DDoS 공격 등에 악용가능
    DDoS 공격 : 대량의 스팸거래를 발생 가능하며 이로 인해 블록체인 서비스가 중단 가능
    상호운영성 미제공 : 책임주체 및 표준규격이 명확하지 않아 예상치 못한 보안위협 발생 가능
    스마트컨트랙트 취약점 : 자산 유출, 개인정보 침해, DDoS 공격 등에 악용가능
  Public
    합의가로채기(51%공격) : 참여자 중 과반수 장악하여 블록체인의 합의 과정을 조작
    사이드 체인 내 비정상 거래 : 메인 체인에서 유효하지 않은 자산이 사이드 체인에서 거래 가능
    개인정보 침해 : 거래정보에 대한 참여자의 접근권한 관리 불가로 원장 내 개인정보 침해 가능
    가용성 저하 : 블록체인의 처리속도 한계, 거래정보 급증으로 가용성이 저하
    비정상거래 탐지 불가 : 사기거래, 자금세탁, 이중지불 등의 거래가 발생 가능
  Private
    권한 오남용 : 금융회사 및 내부직원에 의한 보안사고 등 발생 가능
    내부 담합 : 악의적 담합에 의한 거래 내역의 변조 및 블록 발행 제한
대응방안
  공통 대응방안
    키 관리
      신뢰성 확보 : 신뢰 가능한 기관에서 발간한 안전한 키 저장 및 보관에 대한 최신 보안 가이드 준수
      다중서명 : 거래 서명에 다중 서명기술(multi signature)을 적용하여 공격자가 거래 서명에 필요한 모든 키를 획득하지 않는 한 불법 거래를 시도하지 못하도록 대응
      키 분리 : 업무 및 용도(거래 서명, 거래 메시지 암․복호화 등)별로 키를 구분하여 사용함으로써 키 유출로 인한 피해를 해당 키가 사용되던 업무로 제한
      재생공격 방지 : 공격자가 키를 재생성 하지 못하도록 키를 안전한 방식으로 생성 및 검증
    거래 검증 및 합의
      모니터링 : 내, 외부 공격자에게 장악된 노드로 인해 거래 유효성이 조작되지 않도록 차단
      거래 수수료 : 특정 노드가 대량의 거래를 처리하기 어렵도록 거래 처리량을 제한
    참여자 권한 관리
      3자 접근통제 : 블록체인에서 개인정보 침해가 발생하지 않도록 거래와 무관한 사용자 접근을 통제
      거버넌스 확립 : 거래에 대한 내부직원의 서명을 식별 및 통제 가능하도록 내부 거버넌스 통제 절차를 수립
    블록체인S/W 보안
      최신상태 유지 : 블록체인 플랫폼 및 응용프로그램, 관련 라이브러리 등의 블록체인 S/W 취약점 제거를 위한 최신 상태 유지
      스마트 계약 취약점 탐지 : 스마트 컨트랙트 배포 이전에 코드 검토를 통해 보안 취약점 존재 여부와 악성코드 감염 여부를 확인

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
