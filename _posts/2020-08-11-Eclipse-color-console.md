---
layout: post
title: Springboot, Eclipse 콘솔창 로그 컬러로 출력하기
category: ['Old Posts']
published: false
keywords:
  - eclipse
  - color console
  - font color
  - eclipse console color
  - eclipse ansi console
  - springboot
  - springboot log
---

### 1. 이클립스 플러그인 다운로드

Marketplace > ANSI Escape in Console (by Mihai Nita) 다운로드

<br/>

### 2. 로그 포맷 설정

로그 포맷은 value 부분을 가지고 각자 응용하시면 됩니다. 저는 property로 저장해둔 코드를 첨부합니다.

```xml
<property name="COLOR_LOG_PATTERN" value="%d{yyyy-MM-dd HH:mm:ss.SSS} %boldGreen(%-5level) %boldMagenta(${PID:-}) %cyan(%t) %yellow(%class{36}_%M) %boldWhite(L:%L) %white(%logger{36}) %n %boldRed(     >>>) %m%n"/>
```

<br/>

### 3. 결과화면

[//]: # (![eclipse color console]&#40;{{"/images/posts/eclipsecolorconsole.png"| relative_url}}&#41;)
