---
title: "Java 基础（三）：流程控制"
meta_title: "Java 基础（三）"
description: "if/else、switch、for、while 的常见用法"
date: 2026-01-28T08:00:00Z
categories: ["Java 基础"]
author: "codeguy"
tags: ["java", "基础"]
draft: false
---

流程控制用于实现分支与循环逻辑。

## 1. 条件判断

```java
if (score >= 60) {
 System.out.println("通过");
} else {
 System.out.println("未通过");
}
```

## 2. switch

```java
switch (day) {
 case 1 -> System.out.println("周一");
 case 2 -> System.out.println("周二");
 default -> System.out.println("其他");
}
```

## 3. 循环

```java
for (int i = 0; i < 3; i++) {
 System.out.println(i);
}

int i = 0;
while (i < 3) {
 i++;
}
```
