---
layout: post
title: Linux/리눅스 자주 쓰는 명령어 정리
category: ['Old Posts']
published: false
keywords:
  - 리눅스
  - linux
  - 명령어
  - command
---

### Linux 명령어 정리

- <span class="accent">pwd</span> - 현재 위치한 경로 표시
- <span class="accent">cd</span> - 현재 위치한 경로 이동
- <span class="accent">ls</span> - 현재 폴더의 폴더/파일들의 이름 표시
- <span class="accent">ls -l</span> - 현재 폴더내 폴더/파일들의 이름, 퍼미션, 파일수 등 상세정보 표시
- <span class="accent">ls -al</span> - 현재 폴더내 폴더/파일 (숨김파일 포함) 들의 이름, 퍼미션 등 상세정보표시
- <span class="accent">cp</span> - 폴더/파일 복사
- <span class="accent">cp -r</span> - 폴더/파일 및 하위경로까지 복사
- <span class="accent">mv</span> - 폴더/파일 이동
- <span class="accent">rm</span> - 폴더/파일 삭제 (삭제전 확인)
- <span class="accent">rm -r</span> - 폴더/파일 및 하위경로까지 삭제
- <span class="accent">mkdir</span> - 폴더 생성
- <span class="accent">cat</span> - 파일의 내용을 화면에 출력
- <span class="accent">more</span> - 화면 단위로 파일의 내용을 출력
- <span class="accent">find</span> - 폴더/파일 검색
- <span class="accent">find -name</span> - 특정 이름의 폴더/파일 검색
- <span class="accent">find / -name '파일명'</span> - 모든 경로에서 파일명 검색
- <span class="accent">touch</span> - 크기가 0인 파일 생성
- <span class="accent">chown</span> [소유자:소유그룹] [폴더/파일명] - 폴더/파일의 소유자 변경
- <span class="accent">chmod</span> [옵션] [퍼미션] [폴더/파일명] - 폴더/파일의 퍼미션 변경
- <span class="accent">chgrp</span> [옵션] [그룹] [폴더/파일명] - 폴더/파일의 소유 그룹 수정
- <span class="accent">tar -cvf</span> [압축파일.tar] [폴더/파일명] - tar로 압축하기
- <span class="accent">tar -xvf</span> [압축파일.tar] - tar로 압축풀기
- <span class="accent">tar -zcvf</span> [압축파일.tar.gz] [폴더/파일명] - tar.gz로 압축하기
- <span class="accent">tar -zxvf</span> [압축파일.tar.gz] - tar.gz로 압축풀기
- <span class="accent">gzip</span> [폴더/파일명] - gz로 압축하기
- <span class="accent">gzip -d</span> [압축파일.gz] - gz로 압축풀기
- <span class="accent">yum</span> - 인터넷을 연결해서 rpm 패키지 설치
- <span class="accent">yum install nano -y</span> - Nano 에디터 설치
- <span class="accent">crontab</span> - 반복작업 관리
- <span class="accent">free</span> - 시스템 메모리 정보 출력
- <span class="accent">ps</span> - 현재 실행되고 있는 프로세스 목록 출력
- <span class="accent">pstree</span> - 프로세스의 정보를 트리 형식으로 출력
- <span class="accent">top</span> - 실시간으로 시스템 상황 모니터링
- <span class="accent">killall</span> [프로세스명] - 특정 이름의 프로세스를 모두 종료
- <span class="accent">kill -9</span> [PID] - 특정 PID를 가진 프로세스 종료
- <span class="accent">shutdown</span> - 시스템 종료
- <span class="accent">poweroff</span> - 시스템 종료
- <span class="accent">reboot</span> - 시스템 재부팅
- <span class="accent">shutdown -r now</span> - 시스템 재부팅
- <span class="accent">ping</span> - IP 네트워크를 통해 특정한 호스트가 도달할 수 있는지의 여부를 테스트
- <span class="accent">ifconfig</span> - 리눅스 네트워크 인터페이스 설정 확인/관리
- <span class="accent">netstat</span> - 네트워크 접속, 라우팅 테이블, 네트워크 인터페이스의 통계 정보를 보여주는 도구
- <span class="accent">netstat -ntlp</span> - 현재 열려있는 포트 확인
- <span class="accent">traceroute</span> - 네트워크를 통해 목적지에 도달하는 경로를 수집하는 리눅스 명령어
- <span class="accent">route</span> - 리눅스에서 route 설정 상태 확인하는 명령어
- <span class="accent">clock</span> - 하드웨어 시계 조회/설정하는 리눅스 명령어
- <span class="accent">date</span> - 시스템 날짜, 시간을 출력 또는 변경하는 리눅스 명령어
