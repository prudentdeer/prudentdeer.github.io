---
title: 리버스프록시
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
      I. 역방향의 프록시 서버, 리버스프록시
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 리버스프록시의 정의
        </div>
        <div class="para-cntnt">
            외부에서 내부로 접속시 보안, 라우팅, 부하분산, 서버정보은닉 역할 역방향 프록시 서버
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 리버스프록시
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 리버스프록시의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/리버스프록시.png" alt="리버스프록시">
<!--            <figcaption>Source: Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 리버스프록시의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          특징 보부성무
  보안강화 - 서버에 대한 정보 은닉 및 접근 차단을 위한 방어 역할
  부하분산 - 여러 서버로 부하를 분산하거나 데이터 버퍼링 역할
  성능향상 - 캐싱 기능과 트래픽 분산 기능을 결합시켜 전반적인 서버 서능 향상
  무중단배포 - 서비스 이용이 중단되는 경험 없이 그대로 서비스를 이용
사용방법과 설정방법
  로드밸런서 사용 동작원리와 설정방법
    Round Robin / Least Conn / IP HASH / Weight
  라우팅 사용 동작원리와 설정방법
    Subdomain / Port forwarding / Config / 포트 수정
리버스프록시와 사이버대피소 DDoS 방어측면 비교
  공통 - DDoS 방어가능
  역할 - 서버은닉 &lt;&gt; 트래픽 수용
  원리 - 프록시역할 &lt;&gt; DNS 변경
  대상 - 개인, 기업 &lt;&gt; 중소기업
  관리 - 개인, 기업 &lt;&gt; KISA
포워드프록시와 리버스프록시 비교
  위치 - 클라이언트 앞 &lt;&gt; WEB/WAS 서버 앞
  통신대상 - 클라이언트와 Proxy 서버 &lt;&gt; Proxy 서버와 내부 서버
  EndPoint - 실제서버 도메인 &lt;&gt; 프록시서버의 도메인
  은닉 - 클라이언트 정보 &lt;&gt; 서버 정보

- 서버 앞단에 프록시를 두게 되면 서버는 인터넷으로부터 숨겨진다.
- 외부에서는 서버의 IP를 알 수 없을 것 이다.
- 이렇게 되면 공격자는 DDoS 등의 공격 대상으로 실제 서버를 두기 어려울 것 이다. 
- 즉, 공격자는 리버스 프록시 서버만 공격 대상으로 설정할 수 있을 것 이다.

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
