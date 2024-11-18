---
layout: post
title: Docker/도커 자주 쓰는 명령어 정리
category: ['Old Posts']
published: false
keywords:
  - Docker
  - docker
  - 도커
  - command
  - 명령어
---

### Docker

- docker 이미지 조회

  ```
  docker images
  ```

- docker 이미지 검색

  ```
  docker search <image name>
  ```

- docker 이미지 다운로드

  ```
  docker pull <image name>:<tag>
  ```

- docker 이미지 압축, 저장

  ```
  docker save -o <zip file name.tar> <image name>
  ```

- docker 압축, 저장이미지 불러오기

  ```
  docker load -i <zip file name.tar>
  ```

- docker 이미지 삭제

  ```
  docker rmi <image name>:<tag>
  ```

- docker 이미지명, 태그명 변경

  ```
  docker image tag <old image name>:<old tag> <new image name>:<new tag>
  ```

<br/>

### Container

- docker 컨테이너 리스트 조회

  ```
  docker ps // 실행중인 컨테이너 리스트
  docker ps -a // 실행했던 모든 컨테이너 리스트 (종료된 컨테이너 포함)
  ```

- docker 컨테이너 이름 변경

  ```
  docker rename <old name> <new name>
  ```

- docker 이미지로부터 컨테이너 생성 & 실행

  ```
  docker run -itd -p <host port>:<docker port> --name <container name> <image name>:<tag> /bin/zsh
  -i // interactive, 표준입력 활성화
  -t // tty, 가상 터미널 환경 사용(shell)
  -d // detached, 컨테이너가 백그라운드로 실행(데몬 모드)
  ```

- docker 종료되었던 컨테이너 실행

  ```
  docker start <container id>
  ```

- docker 컨테이너 접속

  ```
  docker attach <container id>
  ```

- docker 컨테이너 종료

  ```
  docker stop <container id>
  ```

- docker 컨테이너 삭제

  ```
  docker rm <container id>
  ```

- docker 컨테이너 내부로 파일 복사

  ```
  docker cp <host 파일 경로> <container name>:<container 내부 경로>
  ```

- docker 외부로 파일 복사

  ```
  docker cp <container name>:<container 내부 경로> <host 파일경로>
  ```
