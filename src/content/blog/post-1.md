---
title: "Java 基础（一）：环境与第一个程序"
meta_title: "Java 基础（一）"
description: "安装 JDK，配置环境变量，并运行 Hello World"
date: 2026-02-02T08:00:00Z
categories: ["Java 基础"]
author: "codeguy"
tags: ["java", "基础"]
draft: false
---

本篇从最基本的环境搭建开始，确保能顺利运行 Java 程序。

## 1. 安装 JDK

- 推荐使用 LTS 版本（如 17）
- 安装后确认 `java -version` 与 `javac -version`

## 2. 配置环境变量

- 设置 `JAVA_HOME`
- 将 `JAVA_HOME/bin` 加入 `PATH`

## 3. 第一个程序

```java
public class Main {
 public static void main(String[] args) {
  System.out.println("Hello, Java!");
 }
}
```

运行方式：

```bash
javac Main.java
java Main
```
