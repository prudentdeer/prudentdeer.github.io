---
layout: post
title: Logback 컬러로 출력하기
category: ['Old Posts']
published: false
keywords:
  - logback
  - color console
  - font color
  - intellij console color
  - intellij ansi console
  - springboot
  - springboot log
  - springboot logback
---

### 1. Gradle 의존성추가

```xml
implementation group: 'org.fusesource.jansi', name: 'jansi', version: '2.4.0'
```

<br/>

### 2. logback.xml 설정예제

withJansi와 pattern부분만 설정하면 됩니다.

```xml
<?xml version="1.0" encoding="UTF-8"?>

<configuration>

    <appender name="console" class="ch.qos.logback.core.ConsoleAppender">
        <withJansi>true</withJansi>
        <encoder>
            <pattern>%white(%d{yyyy-MM-dd HH:mm:ss}) %highlight(%-5level) %msg %n</pattern>
        </encoder>
    </appender>

    <springProfile name="dev">
        <logger name="jdbc" level="OFF"/>
        <logger name="jdbc.connection" level="OFF" />
        <logger name="jdbc.sqlonly" level="OFF" />
        <logger name="jdbc.sqltiming" level="DEBUG" />
        <logger name="jdbc.audit" level="OFF" />
        <logger name="jdbc.resultset" level="OFF" />
        <logger name="jdbc.resultsettable" level="OFF" />

        <root level="INFO">
            <appender-ref ref="console"></appender-ref>
        </root>
    </springProfile>

    <springProfile name="prd">
        <logger name="jdbc" level="OFF"/>
        <logger name="jdbc.connection" level="OFF" />
        <logger name="jdbc.sqlonly" level="OFF" />
        <logger name="jdbc.sqltiming" level="OFF" />
        <logger name="jdbc.audit" level="OFF" />
        <logger name="jdbc.resultset" level="OFF" />
        <logger name="jdbc.resultsettable" level="OFF" />

        <root level="INFO">
            <appender-ref ref="console"></appender-ref>
        </root>
    </springProfile>
</configuration>
```

<br/>

### 3. 결과화면

[//]: # (![eclipse color console]&#40;{{"/images/posts/logbackcolor.png"| relative_url}}&#41;)
